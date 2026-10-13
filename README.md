# Showbiz AI Agent

**Không gian làm việc cho đội ngũ nội dung, vận hành kênh và triển khai chiến dịch.**

Gom việc tìm tin, research, dựng nội dung, giao bài, theo dõi KPI, collect link,
report, giấy tờ và tài chính vào một dashboard tiếng Việt. Google Sheets vẫn
có thể là nơi nhập order; hệ thống phụ trách đồng bộ, theo dõi và tổng hợp.

Repo này **phân phối bộ cài và manifest cập nhật**, không phải repo mã nguồn.
Tải được app không đồng nghĩa đã được cấp tài khoản, license hoặc quyền dùng
các dịch vụ bên ngoài. Quản trị viên hỗ trợ thiết lập máy chủ và tích hợp ban đầu.

[Tải bản phát hành](https://github.com/haianhlc99/showbiz-agent-releases/releases/latest)
· [Bản 0.1.3](https://github.com/haianhlc99/showbiz-agent-releases/releases/tag/v0.1.3)
· [Báo lỗi](https://github.com/haianhlc99/showbiz-agent-releases/issues)

## Có thể làm gì với Showbiz AI Agent?

Luồng làm việc điển hình:

**Tìm tin → kiểm chứng/research → dựng bài → giao việc → thu thập bằng chứng
→ theo dõi KPI → report/nghiệm thu → tổng hợp lương và doanh thu.**

Các nhóm chức năng bên dưới mô tả khả năng trong hệ thống hiện tại. Khả năng sử
dụng thực tế phụ thuộc module được cấp, cấu hình máy chủ, quyền tài khoản và
tình trạng dịch vụ nguồn; không phải mọi module tự hoạt động ngay sau khi cài app.

### 1. Tìm tin và theo dõi nguồn

- **Cào tin Facebook:** quản lý nguồn Page/nhóm, quét theo lịch và theo dõi kết quả.
- **Cào Threads:** đọc Home Feed, phân loại nội dung, theo dõi bài và lựa chọn
  luồng nhận thông báo.
- **Cào tin báo điện tử:** theo dõi nguồn báo/RSS cho showbiz Việt Nam, quốc tế
  và đời sống.
- **Live Feed:** xem tin, kết quả xử lý và nội dung đã được chuyển tới nơi nhận.
- Cấu hình tần suất, nguồn và nơi nhận theo nhu cầu vận hành; chất lượng phân
  loại vẫn cần người kiểm tra với tin nhập nhằng hoặc thiếu ngữ cảnh.

### 2. Research Lab

- Research chủ đề nóng, drama và dự án từ thông tin đầu vào.
- Tổng hợp nguồn/bằng chứng và đề xuất góc khai thác nội dung.
- Xem tiến độ, kết quả và lịch sử lượt research.
- Chọn nội dung để chuyển tới kênh nhận đã cấu hình.

**AI hỗ trợ biên tập, không thay thế kiểm chứng.** Cần đọc nguồn trước khi đưa
thông tin về danh tính, cáo buộc hoặc suy đoán vào bài đăng.

### 3. Creator Discovery

- Nhập brief và thông tin campaign, lập bộ từ khóa tìm creator.
- Tìm ứng viên qua provider đã cấu hình; hiện có provider TikTok.
- Lọc theo follower, view, engagement, mức hoạt động và độ phù hợp chủ đề.
- Xem điểm phù hợp, chọn shortlist và xuất kết quả.

### 4. Phát hiện sound viral

- Quét mẫu TikTok và quản lý watchlist sound.
- Theo dõi kết quả phát hiện, tín hiệu tăng trưởng và các lượt quét.
- Chuyển thông tin tới nơi nhận thông báo đã chọn.

### 5. Facebook Studio — bài ảnh

- Tạo bài từ nội dung nhập tay, tin nguồn hoặc brief có hỗ trợ AI.
- Đọc nguồn báo/Threads khi truy cập được; hỗ trợ lấy ảnh nguồn và chọn ảnh.
- Với ảnh Facebook đã chèn chữ, hỗ trợ mở tìm kiếm ảnh thủ công; chưa tự bảo
  đảm tìm được ảnh gốc sạch chữ.
- Chọn tỷ lệ, template theo Page và bố cục ghép ảnh trong canvas.
- Editor layer: ảnh, chữ, crop/zoom, tọa độ/kích thước, thứ tự, khóa/ẩn,
  nhân bản, hoàn tác/làm lại.
- Font và vùng chữ theo từng template; tự xuống dòng/điều chỉnh cỡ, cảnh báo
  khi nội dung không vừa khung.
- Một bài có thể chứa nhiều canvas; nhân bản, đổi thứ tự, xuất thử và tải bộ ảnh.
- Lưu bản nháp, đăng hoặc lên lịch theo khả năng kết nối Page.

Template, artwork và font cần được quản trị viên cung cấp/cấu hình cho từng
khách hàng. Không mặc định dùng chung bộ nhận diện của một Page cho mọi khách.

### 6. Facebook Studio — Reels và phân phối

- Kết nối nguồn TikTok và Page Facebook ở tab **Kết nối kênh**.
- Thiết lập luồng phân phối nguồn → đích, khung giờ và khoảng cách giữa bài.
- Lấy bài từ Daily Monitor hoặc quét bổ sung theo cấu hình.
- Cấu hình tần suất quét riêng và chế độ cao điểm theo kênh/sự kiện.
- Xem hàng chờ, tình trạng xử lý và những bài cần can thiệp.

Giao diện Facebook có thể thay đổi. **Đã gửi thao tác** và **đã xác minh đăng
thành công** là hai trạng thái khác nhau; cần kiểm tra kết quả khi có cảnh báo.

### 7. Tạo content seeding

- Soạn gợi ý comment, reply và nội dung thread theo brief.
- Điều chỉnh nội dung trước khi sử dụng.
- Không nên xem nội dung AI đề xuất là nội dung đã được duyệt hoặc đã đăng.

### 8. Kho drama

- Nhập/phân tích thông tin để tổ chức nhân vật, sự kiện, tác phẩm và quan hệ.
- Xem graph và quản lý các thực thể liên quan.
- Phân biệt thông tin đã xác nhận, chưa xác minh, cáo buộc hoặc phủ nhận.
- Giữ ngữ cảnh để phục vụ tra cứu và research sau này.

### 9. Giao task lên bài

- Dùng Google Sheet giao việc, tab mẫu và các tab theo tháng.
- Đồng bộ order, mã order, nhóm kênh, thời điểm bắt đầu, deadline, KPI và ghi chú.
- Gửi giao việc tới nhóm phù hợp qua bot đã được cấu hình.
- Theo dõi bằng chứng theo từng kênh, phân biệt hoàn thành đúng hạn, trễ và
  chưa xác minh đủ; có thao tác duyệt bằng chứng khi cần.
- Tận dụng dữ liệu Daily và lượt kiểm tra deadline theo cấu hình; không quét
  riêng liên tục cho mọi order trong toàn thời gian thực hiện.
- Thu thập link và ghi trạng thái/kênh hoàn thành vào Sheet; giữ lịch sử order
  đã đóng, lọc order đang chạy và thu gọn phần lịch sử.

Đây là công cụ ghi nhận tiến độ và bằng chứng. Các ghi chú vi phạm cần được
người phụ trách xem xét, không coi việc thiếu link là bằng chứng chắc chắn để phạt.

### 10. Daily Monitor

- Quản lý danh sách kênh giám sát, bật/tắt kênh và đồng bộ KPI.
- Kiểm tra TikTok/Facebook theo ngày và tổng hợp kết quả.
- Theo dõi hashtag và chính tả theo lựa chọn cấu hình.
- Chạy thủ công hoặc theo lịch Daily; dữ liệu có thể được tận dụng cho order
  và luồng phân phối đã cấu hình.

### 11. Collect link và report dự án

- **Lấy link bài:** thu thập link theo dự án và điều kiện đã nhập.
- **Lấy link daily dự án dài:** theo dõi các ngày của dự án, bổ sung link/report.
- **Report cuối dự án:** đọc report, cập nhật view/reach và engagement khi nguồn
  hỗ trợ; tổng hợp theo kênh/ngày/dự án.
- Tạo/cập nhật report khách và hỗ trợ bổ sung phần chưa hoàn tất thay vì luôn
  phải chạy lại toàn bộ.
- Kiểm tra Sheet trước khi tạo tác vụ: đọc quyền, tab/cột và dữ liệu đầu vào;
  bước kiểm tra không ghi Sheet hay gửi tin.
- Xem hàng đợi, tiến độ, lỗi từng phần và file kết quả.

Sheet cần đúng cấu trúc mà tính năng đang yêu cầu. Đọc **Yêu cầu Sheet** trên
form; tên cột hợp lệ có thể khác giữa collect dự án và report cuối dự án.

### 12. Tạo giấy tờ và nghiệm thu

- Tạo hợp đồng, biên bản nghiệm thu hoặc **cả Hợp đồng và BBNT** trong một flow.
- Đọc thông tin từ tài liệu/plan, nạp vào form và cho phép chỉnh trước khi tạo.
- Xử lý giá trị tiền và thông tin các bên theo mẫu được cấu hình.
- Chụp hình nghiệm thu và tạo tài liệu trình bày khi đã cấu hình đủ công cụ.
- Tải file kết quả hoặc mở bản lưu Google Drive theo cấu hình máy chủ.

Luôn kiểm tra số tiền, thông tin pháp nhân, điều khoản và file xuất trước khi
gửi khách. Tạo được tài liệu không đồng nghĩa nội dung đã được phê duyệt.

### 13. Tính lương và thưởng

- Đếm bài theo tháng và tổng hợp số liệu phục vụ tính lương/KPI.
- Thiết lập thưởng sự kiện và các nhóm kênh theo dữ liệu đầu vào.
- Tạo/điền bảng tổng hợp từ mẫu đã cấu hình.
- Thiết lập thông báo nhắc cập nhật bảng lương/view/KPI tới nơi nhận phù hợp.

### 14. Theo dõi doanh thu và booking

- Tổng quan doanh thu và dữ liệu theo tháng.
- Quản lý lương cứng, booking kênh Owner và booking lẻ kênh công ty.
- Theo dõi hoa hồng booking công ty, booking ngoài và phí CTV.
- Gắn link bài vào booking, theo dõi giá trị, thanh toán, khoản chưa thu và ghi chú.

### 15. Booking Emails

- Theo dõi email booking qua Gmail đã kết nối.
- Phân tích email, quản lý tình trạng xử lý và nội dung phản hồi/draft.
- Hỗ trợ luồng duyệt và thông báo; cần cấu hình quyền Gmail phù hợp.

### 16. Quản trị và vận hành

- Tài khoản admin/người dùng, phân quyền module và nhiều profile máy chủ.
- **Kết nối dịch vụ:** cấu hình những dịch vụ được code hỗ trợ, kiểm tra kết nối
  và quản lý thông tin xác thực tại máy chủ.
- **Nơi nhận thông báo:** ghép bot/dịch vụ với tác vụ, nhóm hoặc người nhận;
  hỗ trợ Telegram và Zalo theo khả năng dịch vụ.
- Điều phối tác vụ, hàng đợi Chrome, lịch chạy, trạng thái worker và logs.
- Cập nhật app desktop bằng manifest/chữ ký; cập nhật mã nguồn máy chủ là
  luồng riêng và không tự thay thế cho nhau.

Bot Zalo không hỗ trợ đầy đủ mọi thao tác của tài khoản người dùng; không
cam kết tag-all tự động hoặc vượt giới hạn nhóm của gói bot.

## Bản phát hành và nền tảng

| Thành phần | Trạng thái hiện tại |
| --- | --- |
| App macOS Apple Silicon | Đã phát hành 0.1.3 (`darwin-aarch64`) |
| App macOS Intel / Windows / Linux | Chưa có bộ cài được công bố trong repo này |
| Máy chủ Ubuntu | Có quy trình triển khai nội bộ; chưa có bộ cài khách hàng công khai |
| Cập nhật app | Gói có chữ ký updater; manifest chỉ chứa nền tảng đã phát hành |
| Apple signing | App ký ad-hoc, chưa Apple notarization |

Không tải gói Apple Silicon để cài lên Mac Intel, Windows hoặc Ubuntu.
Một gói có chữ ký updater không đồng nghĩa đã được Apple chứng nhận.

## Cài và dùng lần đầu

1. Nhận tài khoản, địa chỉ máy chủ và hướng dẫn kết nối từ quản trị viên.
2. Mở [Releases](https://github.com/haianhlc99/showbiz-agent-releases/releases/latest),
   tải `Showbiz-AI-Agent_0.1.3_darwin-aarch64.app.tar.gz` cho Mac Apple Silicon.
3. Giải nén, đóng app cũ nếu đang mở, giữ bản cũ để phục hồi rồi chuyển
   `Showbiz AI Agent.app` vào Applications.
4. Nếu macOS cảnh báo ứng dụng chưa được xác minh, chỉ tiếp tục theo hướng dẫn
   quản trị viên sau khi kiểm tra nguồn tải; không tắt bảo vệ hệ thống toàn cục.
5. Mở app, chọn/cấu hình máy chủ và đăng nhập bằng tài khoản được cấp.
6. Admin cấu hình license, dịch vụ, danh sách kênh, mẫu Sheet/template và nơi
   nhận thông báo; thử kiểm tra/preview trước khi bật gửi hoặc chạy tự động.

Khách kết nối máy chủ qua LAN/VPN cần kết nối được mạng đó. App không tự cài
VPN, không tự cấp tài khoản mạng và không mặc định mở máy chủ ra Internet.

## Có cần cài Python, Node hay môi trường lập trình?

**App Mac đã kèm Node runtime, giao diện Next và backend Python đóng gói bằng
PyInstaller.** Không cần tự tạo virtualenv chỉ để mở giao diện; PyInstaller kèm
trình thông dịch và thư viện mà quá trình build thu thập được.

Điều này **không có nghĩa mọi công cụ ngoài đều được cài sẵn**. Các module crawl,
video, OCR hoặc chuyển đổi tài liệu có thể cần Chrome/Chromium, phiên đăng nhập,
FFmpeg, Tesseract, LibreOffice hoặc tài nguyên/mẫu riêng trên máy chạy tác vụ.
Triển khai backend local đầy đủ vẫn cần kiểm thử từng module trên máy sạch.

Nếu tác vụ chạy trên máy chủ Ubuntu, quản trị viên thiết lập môi trường và các
công cụ ở **máy chủ**; người dùng chỉ cần app/trình duyệt và quyền kết nối.
Quy trình triển khai Ubuntu nội bộ hiện cài Python/virtualenv, Node, thư viện,
trình duyệt và các công cụ hệ thống. Chưa coi đó là bộ cài thương mại một chạm.

## Tích hợp và chi phí ngoài

- Google Sheets/Drive: OAuth, quyền truy cập file và thư mục do khách/admin cấp.
- Gmail: kết nối riêng khi dùng Booking Emails.
- Telegram/Zalo: cần bot và đích nhận đúng; các giới hạn phụ thuộc dịch vụ/gói.
- AI, tìm kiếm hoặc crawler provider: cần key và ngân sách khi tính năng dùng
  dịch vụ đó. Không phải mọi tính năng đều cần cùng một bộ key.
- Chi phí API, lưu trữ, hạ tầng và dịch vụ ngoài không được mặc định bao gồm
  chỉ vì tải bộ cài từ repo này.

Không chia sẻ token, mật khẩu, cookie, OAuth JSON hoặc bản export chứa dữ liệu
khách hàng trong issue công khai.

## Cập nhật và giới hạn cần biết

- Vào **Cài đặt ứng dụng → Cập nhật ứng dụng trên thiết bị này** để kiểm tra bản
  mới khi app có cấu hình updater. Lưu công việc trước khi cài và mở lại.
- App cũ chưa có updater cần cài thủ công bản chuyển tiếp một lần.
- Bản 0.1.3 đã kiểm tra chữ ký, checksum tải lại và mở app từ gói; chu trình nâng
  bản/cài/mở lại qua updater thật vẫn cần thử nội bộ trước triển khai rộng.
- Đổi app không tự migrate toàn bộ máy chủ, cấu hình, font/template hay dữ liệu.
- Không bảo đảm thu được mọi bài: nguồn riêng tư, giới hạn truy cập, phiên hết
  hạn hoặc thay đổi giao diện có thể làm lượt crawl thiếu/lỗi.
- View/reach là số liệu tại lúc thu thập. Bài sửa/xóa hoặc thay đổi quyền xem
  có thể cần kiểm tra lại và bổ sung thủ công.

## Báo lỗi và nhận hỗ trợ

Khi báo lỗi, cung cấp phiên bản app, hệ điều hành/chip, module, các bước tái hiện,
kết quả mong muốn và ảnh màn hình đã che dữ liệu nhạy cảm. Nếu liên quan một task,
gửi mã task/order qua kênh hỗ trợ riêng; không đăng nội dung khách hàng công khai.

Đề xuất tính năng nên kèm tình huống sử dụng, tần suất và mẫu kết quả mong muốn
để ưu tiên đúng nhu cầu vận hành.

## Phạm vi repo

Repo giữ bộ cài, chữ ký, checksum, ghi chú phiên bản và manifest. Không chứa
token của khách, DB, profile Chrome hoặc cấu hình máy chủ đang vận hành.
Repo công khai không phải cam kết mã nguồn mở hay miễn phí mọi module.

Tham khảo về đóng gói: [PyInstaller](https://pyinstaller.org/en/stable/operating-mode.html)
và [Tauri](https://v2.tauri.app/distribute/).
