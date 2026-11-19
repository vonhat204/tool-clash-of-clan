<div align="center">

# NEMRAN · Tool Clash of Clan

**Farm Làng chính theo combo của bạn.**

Tìm trận theo tài nguyên, triển khai đội hình và theo dõi từng phiên giả lập trên Windows.

**[⬇ Tải bản mới nhất](https://github.com/vonhat204/tool-clash-of-clan/releases/latest)**
&nbsp; · &nbsp;
**[🌐 Website NEMRAN](https://nemran-coc-tool.pages.dev/)**
&nbsp; · &nbsp;
**[💬 Hỗ trợ Zalo](https://zalo.me/0363345126)**

Windows 64-bit · MuMuPlayer / LDPlayer 9 · Game English · 1280 × 720

</div>

---

## NEMRAN là gì?

NEMRAN là công cụ hỗ trợ tự động farm Clash of Clans trên giả lập Android. Bạn chọn combo, đặt mục tiêu tài nguyên và điều chỉnh nhịp thả; bot thực hiện vòng tìm trận, tấn công, về làng và kiểm tra nâng tường theo cấu hình.

Kho này cung cấp **bản tải Windows, lịch sử phát hành và thông báo cập nhật**. Mỗi bản có ghi chú riêng trong mục [Releases](https://github.com/vonhat204/tool-clash-of-clan/releases).

## Tính năng chính

- **Tìm mục tiêu theo tài nguyên:** đọc Gold, Elixir và đối chiếu ngưỡng đã đặt trước khi chọn trận.
- **Triển khai theo combo:** dùng đội hình, đường và điểm thả đã thiết lập; đọc số lượng lính, phép và lặp lại điểm khi còn dư.
- **Đường lính và phép cùng màu:** hỗ trợ các hướng đỏ, xanh lá, xanh dương, vàng; khi chọn hướng nào, bot dùng bộ điểm tương ứng của hướng đó.
- **Combo Studio:** thiết lập đội hình, vẽ đường và đặt điểm lính, spell trên bản đồ chiến thuật.
- **Nâng tường theo ngưỡng:** dùng Gold hoặc Elixir theo cấu hình, sau đó thoát bảng nâng và tiếp tục vòng farm.
- **Theo dõi từng thiết bị:** Preview, nhật ký và thống kê; cấu hình và lịch sử được lưu theo phiên giả lập.
- **Xử lý quà xuất hiện trong luồng chơi:** nhận Claim, chạm mở rương/hộp và Continue khi nhận diện được màn tương ứng.
- **Cập nhật trong ứng dụng:** kiểm tra phiên bản, xem ghi chú và chủ động chọn lúc tải, cài bản mới.

## Chuẩn bị trước khi chạy

- Máy tính **Windows 64-bit**.
- Giả lập **MuMuPlayer hoặc LDPlayer 9**, mở sẵn Clash of Clans và cho phép kết nối ADB.
- Độ phân giải giả lập **1280 × 720**, màn hình ngang.
- Ngôn ngữ trong game: **English**.
- Key kích hoạt NEMRAN phù hợp với máy và số phiên sử dụng. Liên hệ [Zalo 0363 345 126](https://zalo.me/0363345126) để được hướng dẫn.

Tải giả lập từ trang chính thức: **[MuMuPlayer](https://www.mumuplayer.com/vi/download/)** · **[LDPlayer 9](https://vnm.ldplayer.net/versions)**.

## Tải và sử dụng lần đầu

1. Mở **[bản phát hành mới nhất](https://github.com/vonhat204/tool-clash-of-clan/releases/latest)**.
2. Trong **Assets**, tải tệp **`NEMRAN-<phiên bản>-windows-x64.zip`**.
3. Giải nén toàn bộ ZIP vào một thư mục. Giữ `NEMRAN.exe` và thư mục `_internal` đi cùng nhau.
4. Mở **`NEMRAN.exe`** và kích hoạt key theo hướng dẫn trong ứng dụng.
5. Mở giả lập và game, đặt đúng độ phân giải/ngôn ngữ rồi bấm **Quét ADB → chọn thiết bị → Kết nối**.
6. Chọn combo, đặt ngưỡng Gold/Elixir, thời gian kết thúc trận và các tùy chọn cần dùng.
7. Bấm **Bắt đầu**, theo dõi **Nhật ký** hoặc **Preview**. Dùng **Dừng** khi cần kết thúc phiên.

Bạn dùng bản EXE đã đóng gói nên **không cần cài Python**.

## Cập nhật lên bản mới

1. Dừng các phiên bot và chờ thao tác hiện tại kết thúc.
2. Vào **Cài đặt → Thông báo → Cập nhật phần mềm NEMRAN**.
3. Bấm **Kiểm tra phiên bản**, đọc nội dung thay đổi rồi chọn **Cập nhật NEMRAN**.
4. Chờ tải và xác minh hoàn tất; chương trình sẽ thay bản phần mềm và mở lại.

Khi cập nhật bằng nút trong ứng dụng, **key, cài đặt, lịch sử và dữ liệu combo riêng được giữ lại**. Cập nhật phần mềm và cập nhật combo có mục thông báo riêng.

Các bản cũ đang dùng kênh tải trước đây cần được nối sang kênh GitHub một lần. Nếu bot chưa thấy bản mới, liên hệ Zalo kèm phiên bản đang dùng để được kiểm tra.

## Câu hỏi thường gặp

<details>
<summary><strong>Cần tải ZIP hay cả latest.json?</strong></summary>

Người dùng tải tệp ZIP trong Assets và giải nén toàn bộ. `latest.json` là thông báo để bộ cập nhật đọc tự động, không phải tệp cài đặt. Các mục `Source code (zip)` và `Source code (tar.gz)` do GitHub hiển thị cũng không phải gói NEMRAN cho Windows.

</details>

<details>
<summary><strong>Quét ADB chưa thấy giả lập thì làm gì?</strong></summary>

Kiểm tra giả lập đã mở và đã cho phép ADB trong cài đặt của giả lập, sau đó bấm Quét ADB lại. Chọn đúng thiết bị cần chạy. Khi cần hỗ trợ, gửi tên/phiên bản giả lập và dòng nhật ký sau khi quét qua Zalo.

</details>

<details>
<summary><strong>Có thể chỉnh combo và tốc độ thả không?</strong></summary>

Combo dùng các đường, điểm lính và phép được thiết lập trong Combo Studio. Đây là công cụ chỉnh combo riêng; gói ZIP Windows trong Releases là Bot chính. Liên hệ Zalo để được hướng dẫn sử dụng bộ chỉnh combo. Nhịp thả được điều chỉnh trong phần cài đặt nâng cao của Bot chính. Sau khi thay đổi, lưu cấu hình rồi thử một trận để kiểm tra kết quả trên giả lập của bạn.

</details>

<details>
<summary><strong>Có cần tài khoản GitHub để tải và cập nhật không?</strong></summary>

Các bản tải trong kho này được công khai. Người dùng có thể tải ZIP và nhận cập nhật mà không cần tài khoản hay token GitHub. Key kích hoạt NEMRAN được quản lý riêng.

</details>

## Liên hệ và hỗ trợ

- **Zalo:** [0363 345 126](https://zalo.me/0363345126).
- **Nhóm COC FARM:** [Tham gia cộng đồng trên Zalo](https://zalo.me/g/yc96pbpljdgy9a078unk).
- **Website:** [nemran-coc-tool.pages.dev](https://nemran-coc-tool.pages.dev/).
- **Lịch sử cập nhật:** [Xem các phiên bản và ghi chú phát hành](https://github.com/vonhat204/tool-clash-of-clan/releases).

Khi báo lỗi, gửi **phiên bản NEMRAN, tên giả lập, combo đang chọn, ảnh màn hình và đoạn nhật ký gần thời điểm lỗi** để hỗ trợ kiểm tra đúng bước.
