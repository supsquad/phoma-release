# Phoma

Desktop app for Android automation — control phones, inspect layouts, build
drag-and-drop automation flows, and run them as tasks.

This repository hosts the Windows installers, named
`phoma-setup-v<version>.exe`, and the release notes below.

## Download

Get the Windows installer from the
[latest release](https://github.com/supsquad/phoma-release/releases/latest) or
from [phomaapp.com](https://phomaapp.com). An installed copy updates itself.
Pre-releases are beta builds.

## Release notes

What each release changes, newest first. Phoma shows these notes on its
About screen, next to an available update and for the version you are running,
in English or Vietnamese.

### v2.0.0-beta.11 — 2026-11-09

**English**

- **Notifications**: Phoma now tells you when something happens to your account: a plan bought or ended, a flow version on the Store approved or rejected, a payout approved, paid or rejected, a team invite or removal.
- **Notifications**: opening one of these takes you to the screen it is about (**Sell**, **Referral** or **Team**) instead of the browser.

**Tiếng Việt**

- **Thông báo**: Phoma báo cho bạn khi có việc xảy ra với tài khoản: mua hoặc hết gói, phiên bản flow trên Cửa hàng được duyệt hay bị từ chối, yêu cầu rút tiền được duyệt, đã chuyển hay bị từ chối, lời mời vào team hay bị gỡ khỏi team.
- **Thông báo**: mở một thông báo như vậy sẽ đưa bạn tới đúng màn liên quan (**Bán flow**, **Giới thiệu** hay **Team**) thay vì mở trình duyệt.

### v2.0.0-beta.10 — 2026-11-07

**English**

- **Apps**: a new **Apps** screen, a library of the apps you put on your phones. Add an .apk or a split bundle (.xapk, .apks, .apkm) from a file, or an app from Google Play, then install it on the phones you pick.
- **Apps**: an app from Google Play installs through the Play Store on each phone. Before sending a file, Phoma checks that the phone's Android version and processor can run it, and explains a failed install in plain words.
- **Agent**: the Agent can list your app library, add apps from Google Play, and install or remove apps on your phones. It asks you every time before it installs or removes anything.
- **Look**: a new, calmer look across the app. Each screen is one panel, colours say what things mean, and versions, IDs and dates line up in a monospaced font. The fonts ship with the app.
- **Phones**: each phone tile shows what the phone is doing: running a flow, connected, waiting for you to allow USB debugging, or failed.

**Tiếng Việt**

- **Kho ứng dụng**: màn **Kho ứng dụng** mới, thư viện các ứng dụng bạn cài lên điện thoại. Thêm tệp .apk hoặc gói chia nhỏ (.xapk, .apks, .apkm) từ máy, hoặc ứng dụng trên Google Play, rồi cài lên các điện thoại bạn chọn.
- **Kho ứng dụng**: ứng dụng từ Google Play được cài qua Play Store trên từng điện thoại. Trước khi gửi tệp, Phoma kiểm tra phiên bản Android và bộ xử lý của điện thoại có chạy được không, và báo lỗi cài đặt bằng lời dễ hiểu.
- **Agent**: Agent xem được thư viện ứng dụng, thêm ứng dụng từ Google Play, cài hoặc gỡ ứng dụng trên điện thoại của bạn. Lần nào cài hay gỡ, Agent cũng hỏi bạn trước.
- **Giao diện**: giao diện mới, dịu mắt hơn trên toàn app. Mỗi màn là một khung, màu sắc cho biết ý nghĩa, còn phiên bản, mã và ngày tháng thẳng hàng nhờ phông chữ đơn cách. Phông chữ đi kèm app.
- **Điện thoại**: mỗi ô điện thoại ghi rõ điện thoại đang làm gì: đang chạy flow, đã kết nối, đang chờ bạn cho phép gỡ lỗi USB, hay bị lỗi.

### v2.0.0-beta.9 — 2026-11-06

**English**

- **Store**: a new **Store** screen to browse flows for sale, see what each one does (its steps, the apps it opens, whether it uses the internet), buy it, and install or update the flows you own.
- **Sell**: a new **Sell** screen to sell your own flows: open a seller account, list a flow, upload new versions, follow reviews and sales, and request payouts. **Sell on the Store** in a flow's menu leads here.
- **Store**: a flow bought from the Store runs and can be renamed or deleted, but it cannot be opened in the editor or shared with a team.
- **Store**: a Store link on phomaapp.com opens the flow's page in the app.

**Tiếng Việt**

- **Cửa hàng**: màn **Cửa hàng** mới để xem các flow đang bán, biết mỗi flow làm gì (các bước, ứng dụng nó mở, có dùng internet không), mua, cài và cập nhật các flow bạn sở hữu.
- **Bán flow**: màn **Bán flow** mới để bán flow của bạn: mở tài khoản người bán, đăng bán flow, tải lên phiên bản mới, theo dõi kết quả duyệt và doanh số, rút tiền. Mục **Bán trên Cửa hàng** trong menu của flow dẫn tới đây.
- **Cửa hàng**: flow mua từ Cửa hàng chạy được, đổi tên hay xóa được, nhưng không mở được trong trình chỉnh sửa và không chia sẻ cho team được.
- **Cửa hàng**: liên kết Cửa hàng trên phomaapp.com mở thẳng trang của flow trong app.

### v2.0.0-beta.8 — 2026-11-06

**English**

- **Account**: create an account in your browser from the sign-in screen, with email or Google; the app signs you in when you are done.
- **Referral**: a new **Referral** screen. Share your invite link, see who joined, and earn free days as people join plus a commission on what they pay, paid to your bank account.
- **Account**: the sign-up, sign-in and password reset pages open in the app's language.

**Tiếng Việt**

- **Tài khoản**: tạo tài khoản trên trình duyệt ngay từ màn đăng nhập, bằng email hoặc Google; xong là app tự đăng nhập.
- **Giới thiệu**: màn **Giới thiệu** mới. Chia sẻ liên kết mời, xem ai đã tham gia, nhận thêm ngày dùng miễn phí khi có người tham gia cùng hoa hồng trên số tiền họ trả, chuyển về tài khoản ngân hàng của bạn.
- **Tài khoản**: các trang đăng ký, đăng nhập và đặt lại mật khẩu mở đúng ngôn ngữ của app.

### v2.0.0-beta.7 — 2026-11-05

**English**

- **Look**: one look across the app. Buttons, fields and dialogs have the same size and style on every screen, and the wording says the same thing the same way in English and Vietnamese.
- **Icons**: icons show without an internet connection.
- **Agent**: signing an agent out, or removing its API key, now says that it deletes the agent.
- **Team**: **Remove from team** is named the same way everywhere, and never deletes the member or the flow.

**Tiếng Việt**

- **Giao diện**: giao diện đồng nhất trên toàn app. Nút, ô nhập và hộp thoại cùng kích thước, cùng kiểu ở mọi màn, cách dùng từ thống nhất cả tiếng Anh lẫn tiếng Việt.
- **Biểu tượng**: biểu tượng hiện đầy đủ cả khi không có mạng.
- **Agent**: lệnh đăng xuất agent hay gỡ API key giờ ghi rõ là sẽ xóa luôn agent.
- **Team**: **Gỡ khỏi team** được gọi cùng một tên ở mọi nơi, và không bao giờ xóa thành viên hay flow.

### v2.0.0-beta.6 — 2026-11-04

**English**

- **Settings**: a new **Settings** screen: the language, whether closing the window keeps Phoma running in the tray, how many runs go at once, the phone screen's quality, and how many steps the Agent may take per message. Every change saves itself.
- **Settings**: the run queue's width and the phone screen settings are remembered after a restart.

**Tiếng Việt**

- **Cài đặt**: màn **Cài đặt** mới: ngôn ngữ, đóng cửa sổ thì Phoma chạy tiếp ở khay hệ thống hay thoát, số lượt chạy cùng lúc, chất lượng màn hình điện thoại, và số bước tối đa Agent được làm cho mỗi tin nhắn. Mọi thay đổi tự lưu.
- **Cài đặt**: độ rộng hàng đợi chạy và thiết lập màn hình điện thoại được nhớ lại sau khi khởi động lại.

### v2.0.0-beta.5 — 2026-11-03

**English**

- **Notifications**: a bell in the top bar shows new notices, with an inbox to read them all and mark them read.
- **Banners**: announcements show at the top of the **Phones**, **Flow** and **Team** screens; a banner you close stays closed.
- **Look**: every screen has a top bar with its name, the bell and the Agent button.

**Tiếng Việt**

- **Thông báo**: chuông trên thanh tiêu đề báo thông báo mới, kèm hộp thư để đọc tất cả và đánh dấu đã đọc.
- **Banner**: thông báo chung hiện ở đầu màn **Điện thoại**, **Flow** và **Team**; banner đã đóng sẽ không hiện lại.
- **Giao diện**: mọi màn có thanh tiêu đề với tên màn, chuông thông báo và nút Agent.

### v2.0.0-beta.4 — 2026-11-02

**English**

- **About**: the Guides and Support links open pages that exist: guides on the phomaapp.com blog, support by email.
- **Updates**: a beta install only updates to beta versions, and a stable install only to stable ones.

**Tiếng Việt**

- **Thông tin**: liên kết Hướng dẫn và Hỗ trợ mở đúng trang: hướng dẫn trên blog phomaapp.com, hỗ trợ qua email.
- **Cập nhật**: bản beta chỉ cập nhật lên bản beta, bản ổn định chỉ cập nhật lên bản ổn định.

### v2.0.0-beta.3 — 2026-10-30

**English**

- **Plans and teams**: buy a plan for your team in the app, invite people by email, and manage members and roles on the new **Team** screen.
- **Team**: share flows with your team. Teammates get their own copy and can update it when you push a new version.
- **Phones**: use a teammate's phone over the internet, or share yours with the teammates you pick. A shared phone works like one plugged into your own computer.
- **Editor**: open several flows at once in tabs, each with its own undo history. Steps on the canvas show what they do.
- **Agent**: an AI agent on every screen that can build flows and work your phones.
- **Account**: sign in to start; each account's data stays separate on a shared computer.

**Tiếng Việt**

- **Gói và team**: mua gói cho team ngay trong app, mời người khác qua email, quản lý thành viên và vai trò ở màn **Team** mới.
- **Team**: chia sẻ flow cho team. Đồng đội nhận bản sao của riêng họ và cập nhật được khi bạn đẩy phiên bản mới.
- **Điện thoại**: dùng điện thoại của đồng đội qua internet, hoặc chia sẻ điện thoại của bạn cho những đồng đội bạn chọn. Điện thoại được chia sẻ dùng như đang cắm vào máy của bạn.
- **Trình chỉnh sửa**: mở nhiều flow cùng lúc trong các tab, mỗi tab có lịch sử hoàn tác riêng. Các bước trên canvas hiện rõ chúng làm gì.
- **Agent**: AI agent có mặt ở mọi màn, dựng được flow và thao tác trên điện thoại của bạn.
- **Tài khoản**: đăng nhập để bắt đầu; dữ liệu của mỗi tài khoản tách riêng khi dùng chung một máy.

### v2.0.0-beta.2 — 2026-10-29

**English**

- **Account**: reset a forgotten password from the sign-in dialog.
- **Editor**: undo, and a warning before you leave a flow with unsaved changes.
- **Phones**: give your phones nicknames, so you can tell them apart everywhere.
- **Run**: scheduled runs start on time again.

**Tiếng Việt**

- **Tài khoản**: đặt lại mật khẩu đã quên ngay từ hộp đăng nhập.
- **Trình chỉnh sửa**: hoàn tác, và cảnh báo trước khi rời một flow còn thay đổi chưa lưu.
- **Điện thoại**: đặt tên gợi nhớ cho điện thoại để phân biệt chúng ở mọi nơi.
- **Chạy**: các lượt chạy theo lịch lại chạy đúng giờ.

### v2.0.0-beta.1 — 2026-10-07

**English**

- The first beta of Phoma 2.0. Sign in with your Phoma account, and buy and install flows from the store.
- **Updates**: the app offers new versions itself.

**Tiếng Việt**

- Bản beta đầu tiên của Phoma 2.0. Đăng nhập bằng tài khoản Phoma, mua và cài flow từ cửa hàng.
- **Cập nhật**: app tự báo khi có phiên bản mới.
