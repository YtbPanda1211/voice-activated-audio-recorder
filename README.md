# voice-activated-audio-recorder
Voice-Activated-Audio-Recorder
---
---
---
### 16/9/2026 : 

🚀 Biến sự im lặng thành khoảng trống biến mất: 
Trải nghiệm ghi âm thông minh thế hệ mới ✨
⏰ Các phần mềm ghi âm truyền thống đang khiến chúng ta lãng phí thời gian: 
bạn phải bấm thủ công liên tục 🖱️, 
tạo ra những file chứa đầy tiếng tạp âm hay khoảng im lặng vô nghĩa 🤫, 
rồi mất công cắt ghép để có 1 đoạn ghi âm ưng ý ✂️.
💡 "Bộ ghi âm thông minh" chạy trực tiếp trên web của tôi ra đời để giải quyết triệt để nỗi đau đó bằng 3 điểm đột phá:
1️⃣ Tự động hóa toàn diện (VAD): 
Hệ thống tự động tạm dừng ⏸️ khi bạn ngừng nói quá số giây bạn cài đặt 
Và tự động ghi tiếp vào đúng bản ghi đó khi bạn nói trở lại 🎙️
Không cần thao tác thủ công,
không còn file rác 🗑️.
2️⃣ Tùy chỉnh linh hoạt theo môi trường: 
Người dùng dễ dàng điều chỉnh độ nhạy nhận tiếng nói 🎚️ và thời gian ngắt quãng ⏳ để thích ứng hoàn hảo với từng không gian thực tế 🏢🏡.
3️⃣ Bảo mật và Tối ưu: 
Xử lý hoàn toàn ngay trên thiết bị (Client-side) 💻🔒, 
dữ liệu nằm gọn trong bộ nhớ tạm để bạn nghe lại 🎧, 
tải xuống 📥 hoặc xóa vĩnh viễn ngay lập tức chỉ với một cú click ❌.
💎 Một công cụ nhỏ, giải phóng những phiền toái lớn — mang lại trải nghiệm ghi chú rảnh tay và thông minh hơn bao giờ hết 🌟.
---
---
---
---
### 19/9/2026 :

## 🎨 Cập nhật tính năng & giao diện mới
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
---
---
### 14/10/2026 :

🚀 NHẬT KÝ CẬP NHẬT & HƯỚNG DẪN SỬ DỤNG HỆ THỐNG GHI ÂM

🎙️ 1. Khởi tạo Chức năng Ghi âm & Chuyển Văn bản
📝 Mô tả chi tiết:
Chuyển giọng nói thành văn bản: Tích hợp Web Speech API để nhận dạng tiếng Việt theo thời gian thực.
Quản lý đa phương tiện: Hỗ trợ lưu trữ bản ghi, phát/nghe lại audio, tải file âm thanh và xuất file văn bản .txt (mã hóa UTF-8 chuẩn).
Thao tác nhanh: Cung cấp nút xóa văn bản để làm sạch nội dung tức thì.
💡 Cách sử dụng:
Nhấn nút Ghi âm và nói vào micro. Văn bản sẽ hiển thị ngay trên màn hình.
Khi dừng ghi, chọn nghe lại âm thanh, tải file audio hoặc tải file .txt về máy.

🔄 2. Nâng cấp Chạy ngầm (Background Recording)
📝 Mô tả chi tiết:
Ghi âm không gián đoạn: Sử dụng MediaRecorder cho phép tiếp tục ghi âm khi chuyển tab hoặc thu nhỏ trình duyệt.
Giữ màn hình luôn bật: Tích hợp Wake Lock API hạn chế thiết bị tự động khóa/tắt màn hình.
Cảnh báo & Thông báo: Hiển thị thông báo trạng thái "Đang ghi âm ngầm" và cảnh báo trước khi tắt tab/rời trang.
Xử lý nền ổn định: Sử dụng bộ hẹn giờ dự phòng (thay thế requestAnimationFrame) để duy trì tiến trình ở trạng thái nền.
💡 Cách sử dụng:
Bắt đầu ghi âm, sau đó có thể thu nhỏ trình duyệt hoặc chuyển sang tab/ứng dụng khác làm việc (lưu ý: không đóng tab).

🎚️ 3. Tăng cường Độ nhạy nhận diện Giọng nói nhỏ & Thì thầm
📝 Mô tả chi tiết:
Tăng độ nhạy tín hiệu: Hạ ngưỡng nhận diện từ 0.015 xuống 0.001.
Xử lý âm thanh chất lượng cao: Dùng dạng Float32 PCM (thay cho 8-bit) giúp bắt trọn sóng âm dao động cực nhỏ.
Khuếch đại riêng biệt: Bổ sung nhánh khuếch đại & compressor riêng cho việc phát hiện giọng nói (không làm ảnh hưởng đến file âm thanh gốc).
Tối ưu bộ lọc: Tắt Noise Suppression để tránh lọc nhầm tiếng thì thầm; duy trì Auto Gain Control và chống nhấp nháy trạng thái.
Thanh điều chỉnh linh hoạt: Bổ sung thanh kéo điều chỉnh độ nhạy từ 0.001 đến 0.120.
💡 Cách sử dụng:
Khi nói nhỏ/nói xa micro: Kéo thanh độ nhạy về mốc nhỏ hơn (ví dụ: 0.001).
Trong môi trường có tiếng ồn nền: Tăng nhẹ độ nhạy lên mốc 0.005 – 0.015.

🔀 4. Phân loại Nguồn âm thanh (Mic & Trình duyệt)
📝 Mô tả chi tiết:
Ghi âm đa nguồn: Hỗ trợ ghi & bóc tách văn bản đồng thời từ cả Micro và Trình duyệt (audio track).
Gán nhãn tự động: Thêm tiền tố nhận diện ở đầu đoạn văn bản:
(Mic): Giọng nói thu qua micro.
(Trình duyệt): Lời thoại/âm thanh phát từ tab trình duyệt.
Bảo toàn dữ liệu: Giữ nguyên bản ghi âm thanh gốc để tải xuống.
💡 Cách sử dụng:
Bật ghi âm. Khi có âm thanh từ mic hoặc cuộc họp/video trên trình duyệt, hệ thống sẽ tự động nhận diện và đính kèm nhãn nguồn tương ứng.

🔧 5. Tối ưu hóa & Sửa lỗi Thu âm từ Micro
📝 Mô tả chi tiết:
Sửa lỗi im lặng: Khắc phục lỗi mic không nhận tiếng bằng cách truyền trực tiếp MediaStreamTrack vào SpeechRecognition.
Cơ chế dự phòng: Tự động chuyển sang chế độ mặc định nếu trình duyệt không hỗ trợ audioTrack.
Thông báo minh bạch: Hiển thị cảnh báo rõ ràng nếu người dùng chưa cấp quyền truy cập micro.
💡 Cách sử dụng:
Khuyên dùng trình duyệt Chrome hoặc Edge.
Cấp đầy đủ quyền truy cập micro cho trang web và bắt đầu nói khi giao diện chuyển sang trạng thái đang nhận dạng.

✏️ 6. Chỉnh sửa & Xem trước Văn bản Thời gian thực
📝 Mô tả chi tiết:
Chỉnh sửa trực tiếp: Cho phép gõ, sửa, xóa văn bản ngay trên giao diện mà không cần tạm dừng.
Đồng bộ liên tục: Khung Xem trước tự động cập nhật theo nội dung vừa chỉnh sửa.
Xuất file chuẩn xác: File .txt xuất ra lưu đúng nội dung thực tế sau khi sửa (vẫn giữ nguyên các nhãn nguồn (Mic) / (Trình duyệt)).
💡 Cách sử dụng:
Nhấp vào khung văn bản để sửa lỗi chính tả.
Kiểm tra nội dung ở khung xem trước và nhấn Tải file .txt để nhận file hoàn chỉnh.

⏱️ 7. Tối ưu Luồng Chép lời Real-time & Sắp xếp dòng
📝 Mô tả chi tiết:
Tự động xuống dòng: Văn bản hiển thị ngay khi nói; mỗi đoạn thoại mới tự động tách thành một dòng riêng.
Thứ tự thời gian: Đoạn nhận diện trước nằm trên, đoạn nhận diện sau nằm dưới.
Tăng độ chính xác: Phân tích 3 phương án nhận dạng cùng lúc và tự động chọn kết quả tối ưu nhất.
Tự động khôi phục: Tự động khởi động lại (auto-restart) tiến trình nếu trình duyệt vô tình làm ngắt kết nối.
💡 Cách sử dụng:
Nhấn Bắt đầu nghe, hệ thống sẽ tự động chuyển giọng nói thành văn bản và sắp xếp các dòng theo dòng thời gian thực.

📐 8. Chuẩn hóa Phạm vi Ngưỡng nhận diện Giọng nói
📝 Mô tả chi tiết:
Cập nhật dải điều chỉnh độ nhạy mới tối ưu hơn:
Nhỏ nhất: 0.012
Lớn nhất: 0.200
Bước nhảy: 0.001
Mặc định: 0.200
💡 Cách sử dụng:
Kéo thanh trượt trên màn hình trong khoảng 0.012 – 0.200 để thích ứng với độ ồn môi trường xung quanh.

⚡ 9. Tối ưu hóa Tốc độ Nói nhanh & Độ chính xác Chính tả
📝 Mô tả chi tiết:
Mở rộng phương án: Tăng lên 5 phương án nhận dạng song song để lọc ra kết quả chính xác nhất.
Giảm độ trễ: Giảm thời gian khởi động lại của SpeechRecognition từ 250ms xuống 80ms, tránh mất từ/nuốt chữ khi nói nhanh.
Chuẩn hóa dữ liệu: Tự động làm sạch Unicode tiếng Việt, khoảng trắng và dấu câu; tắt Auto Gain trên mic để giữ nguyên tín hiệu gốc.
💡 Cách sử dụng:
Bạn có thể nói với tốc độ bình thường hoặc nói nhanh, hệ thống vẫn đảm bảo chép lời liên tục và chính xác.

✍️ 10. Sửa lỗi Thiếu ký tự & Tự động Xuống dòng theo Câu
📝 Mô tả chi tiết:
Sửa lỗi Regex: Khắc phục triệt để sự cố làm mất các ký tự tiếng Việt (như t, r, n).
Ngắt câu thông minh: Tự động xuống dòng mới khi kết thúc câu bằng các dấu câu (., !, ?).
Bảo toàn dữ liệu ngắt quãng: Giữ lại đoạn văn bản tạm thời cuối cùng khi trình duyệt tạm dừng và xuất file .txt chứa ký tự xuống dòng chuẩn (thay vì chuỗi \n).

💡 Cách sử dụng:
Nói rõ ràng trọn câu. Khi kết thúc câu bằng dấu câu, hệ thống sẽ tự động ngắt dòng sạch sẽ trên màn hình lẫn trong file .txt tải về.

---
------
---
👇 Trải nghiệm thử miễn phí tại đường link dưới đây: 
https://ytbpanda1211.github.io/voice-activated-audio-recorder/ 
