# AI Support Log

## 1. Thông tin người nộp

- **Họ và tên:** Lê Duy Bảo

- **Mã học viên:** 2A202602749

- **Tên nhóm:** BLBD

- **Case:** Case B — AI Notes: Personal Learning Notes

- **Phần việc cá nhân:** Option C

## 2. AI hỗ trợ theo hoạt động

| Hoạt động | Có dùng AI? | AI hỗ trợ gì? | Tôi/nhóm quyết định gì? |
|---|---|---|---|
|OCR data và tạo Knowledge base từ slides | Có | Hỗ trợ đưa slide mẫu vào prototype và viết câu hỏi mô phỏng | Dùng cùng bộ slide làm dữ liệu bài học; không coi đó là ghi chú thật của user |
| Mock output | Có | Tạo các content của từng component | Tạo thêm ghi chú cho interactive flow với coach, cụ thể như *Kho local trình duyệt này: coach ở nơi khác chưa thấy-cần Supabase để chia sẻ (BLOCKED).*   |
| Prototype | Có | Tạo và chỉnh sửa các component theo ý tưởng thiết kế, chạy smoke test | Tôi yêu cầu sửa cách chọn chữ và giới hạn quyền của AI |
| Viết tài liệu | Có | Tạo mẫu README, mô tả workflow của prototype | Tôi đối chiếu với prototype và sửa phần không khớp |

## 3. Một ví dụ AI trả lời chưa phù hợp

**AI đã đề xuất:** Ban đầu, AI triển khai thao tác khoanh vùng trên slide tự động chuyển sang hỏi trợ giảng AI.

**Vấn đề:** Không phải mọi vùng được chọn đều cần AI giải thích. Học viên có thể muốn lưu thành ghi chú cá nhân hoặc gửi yêu cầu hỗ trợ cho lab coach. Hành vi tự động hỏi AI chưa phản ánh đúng ý tưởng sản phẩm của tôi.

**Tôi đã sửa:** Tôi yêu cầu AI bổ sung ba lựa chọn Lưu vào ghi chú / Hỏi trợ giảng / Yêu cầu hỗ trợ, áp dụng cho cả chọn chữ và khoanh vùng, đồng bộ với tab panel. AI đã hoàn thiện các luồng: lưu note đúng phân cấp chương/bài/slide; đưa nội dung vào câu hỏi AI mock để học viên chủ động gửi; tạo yêu cầu hỗ trợ để coach xem và trao đổi với học viên.

**Bài học:** AI có thể triển khai đầy đủ chức năng nhưng vẫn hiểu sai mục đích của thao tác. Tôi cần xác định rõ lựa chọn của người dùng, đích xử lý và thời điểm gửi; đồng thời kiểm tra luồng từ thao tác trên slide đến ghi chú, trợ giảng hoặc coach.
