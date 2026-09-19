# voice-activated-audio-recorder
Voice-Activated-Audio-Recorder

16/9/2026 : 
🚀 Biến sự im lặng thành khoảng trống biến mất: Trải nghiệm ghi âm thông minh thế hệ mới ✨
⏰ Các phần mềm ghi âm truyền thống đang khiến chúng ta lãng phí thời gian: bạn phải bấm thủ công liên tục 🖱️, tạo ra những file chứa đầy tiếng tạp âm hay khoảng im lặng vô nghĩa 🤫, rồi mất công cắt ghép để có 1 đoạn ghi âm ưng ý ✂️.
💡 "Bộ ghi âm thông minh" chạy trực tiếp trên web của tôi ra đời để giải quyết triệt để nỗi đau đó bằng 3 điểm đột phá:
1️⃣ Tự động hóa toàn diện (VAD): Hệ thống tự động tạm dừng ⏸️ khi bạn ngừng nói quá số giây bạn cài đặt và tự động ghi tiếp vào đúng bản ghi đó khi bạn nói trở lại 🎙️. Không cần thao tác thủ công, không còn file rác 🗑️.
2️⃣ Tùy chỉnh linh hoạt theo môi trường: Người dùng dễ dàng điều chỉnh độ nhạy nhận tiếng nói 🎚️ và thời gian ngắt quãng ⏳ để thích ứng hoàn hảo với từng không gian thực tế 🏢🏡.
3️⃣ Bảo mật và Tối ưu: Xử lý hoàn toàn ngay trên thiết bị (Client-side) 💻🔒, dữ liệu nằm gọn trong bộ nhớ tạm để bạn nghe lại 🎧, tải xuống 📥 hoặc xóa vĩnh viễn ngay lập tức chỉ với một cú click ❌.
💎 Một công cụ nhỏ, giải phóng những phiền toái lớn — mang lại trải nghiệm ghi chú rảnh tay và thông minh hơn bao giờ hết 🌟.


19/9/2026 :
## 🎨 Cập nhật tính năng & giao diện mới
---
### 1️⃣ Chuyển đổi giao diện Sáng / Tối (Dark / Light Mode)
* **Chức năng mới**:
* 1.1 🌙/☀️ Thêm nút **Chế độ tối / Chế độ sáng** ở góc trên bên phải.
* 1.2 🌗 Tích hợp biểu tượng mặt trăng (tối) và mặt trời (sáng).
* **Phạm vi giao diện tối**:
* 1.3 🖼️ Nền trang
* 1.4 🎙️ Khung ghi âm
* 1.5 🎚️ Thanh chỉnh âm thanh
* 1.6 🕹️ Nút điều khiển
* 1.7 📄 Khung kết quả bản ghi
* **Hướng dẫn sử dụng**:
* 1.8 💾 Lựa chọn lưu bằng `localStorage` (giữ trạng thái khi F5/mở lại).
* 1.9 🖥️ Tự động nhận diện theo theme hệ điều hành nếu chưa chọn thủ công.
---
### 2️⃣ Ghi âm kết hợp (Mic + Trình duyệt / Thiết bị)
* **Chức năng mới**:
* 2.1 🎛️ Thêm công tắc **“Ghi âm âm thanh trình duyệt / thiết bị”**.
* **Trạng thái hoạt động**:
* 2.2 🔴 **Khi tắt**: Chỉ ghi âm từ micro.
* 2.3 🟢 **Khi bật**: Ghi đồng thời giọng nói từ mic + âm thanh tab/cửa sổ/màn hình (trộn chung 1 bản ghi).
* **Tính linh hoạt trong phiên**:
* 2.4 ⚡ Bật/tắt ngay khi đang ghi (tắt giữa chừng $\rightarrow$ các đoạn sau chỉ ghi mic, đoạn trước giữ nguyên).
* 2.5 🧠 VAD (phát hiện tiếng nói) độc lập từ mic, âm thanh trình duyệt không ảnh hưởng bộ đếm im lặng.
* **Hướng dẫn sử dụng**:
* 2.6 1️⃣ Bật công tắc ghi âm trình duyệt/thiết bị.
* 2.7 2️⃣ Nhấn **Bắt đầu nghe**.
* 2.8 3️⃣ Chọn tab/cửa sổ/màn hình trong hộp thoại trình duyệt.
* 2.9 4️⃣ Tích chọn **Chia sẻ âm thanh (Share audio)**.
* 2.10 🎤 Cho phép quyền truy cập micro.
---
### 3️⃣ Chỉ ghi âm trình duyệt / thiết bị (Solo System Audio)
* **Trạng thái Khi bật**:
* 3.1 🔒 Tự động kích hoạt ghi âm trình duyệt/thiết bị, vô hiệu hóa âm thanh mic vào file.
* 3.2 🚫 Khóa công tắc âm thanh trình duyệt để tránh cấu hình sai (có thể bật ngay khi đang ghi).
* **Trạng thái Khi tắt**:
* 3.3 🔄 Khôi phục tùy chọn trước đó (Chỉ ghi mic / Ghi mic + trình duyệt).
* 3.4 👂 Vẫn dùng mic ngầm để detect giọng nói (tự động tạm dừng), nhưng **không lưu audio mic** vào file.
* **Thay đổi chính**:
* 3.5 🛡️ Không yêu cầu quyền micro lúc đầu.
* 3.6 🔇 Không cần phát âm/nói chuyện vào mic.
* 3.7 ▶️ Bản ghi chạy ngay lập tức theo audio trình duyệt.
* 3.8 ⏸️ Tự động pause/resume dựa trên mức âm thanh nguồn trình duyệt.
* **Hướng dẫn sử dụng**:
* 3.9 1️⃣ Bật toggle **Chỉ ghi âm trình duyệt / thiết bị**.
* 3.10 2️⃣ Nhấn **Bắt đầu nghe**.
* 3.11 3️⃣ Chọn nguồn (tab/cửa sổ/màn hình) + bật **Chia sẻ âm thanh**.
* 3.12 🎵 Phát video/nhạc thoải mái không cần thoại.
* 3.13 ⚠️ Tắt giữa chừng $\rightarrow$ trang bật lại yêu cầu quyền mic để trả về chế độ 1 hoặc 2.

👇 Trải nghiệm thử miễn phí tại đường link dưới đây: 
https://ytbpanda1211.github.io/voice-activated-audio-recorder/ 
