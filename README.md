# Track1_Day19_2A202602749_LeDuyBao

## 1. Thông tin cá nhân và nhóm
- **MHV:** 2A202602749
- **Họ tên:** Lê Duy Bảo
- **Tên nhóm:** BLBD
- **Thành viên:** 
**Thành viên:**

| STT | Họ và tên | Mã học viên |
|---|---|---|
| 1 | Lê Duy Bảo | 2A202602749 |
| 2 | Nguyễn Đình Anh Đức | 2A202602856 |
| 3 | Vũ Quốc Bảo | 2A202602829 |

- **Case:** Case B — AI Notes: Personal Learning Notes

## 2. Hypothesis Problem
Khi ôn lại sau các buổi học, học viên có ghi chú/highlight trong lúc học gặp khó khăn trong việc tìm lại và hiểu lại nội dung quan trọng để ôn tập vì ghi chú nằm rời rạc theo từng slide hoặc được chép thô theo lời giảng, chưa được chắt lọc, dẫn đến mất thời gian quay lại slide/video để đối chiếu, và vẫn khó nhớ hoặc hiểu bài khi cần dùng.

Chi tiết ở [three-option-design-sheet.md](three-option-design-sheet.md).

## 3. Three Solution Options
- Option A — User tự viết, hệ thống chỉ gom theo mục: User tự highlight và viết ghi chú theo mẫu gồm ý chính, điểm chưa hiểu và câu hỏi cần giải đáp. Hệ thống chỉ sắp xếp các highlight theo slide, không diễn giải hoặc viết nội dung thay user.
- Option B — AI hỏi gợi mở, user tự tạo nội dung ghi chú: User bôi đen trực tiếp một đoạn trên slide và chọn Highlight hoặc Chưa hiểu. AI đặt câu hỏi dựa trên đoạn đã chọn; câu trả lời của user được lưu thành ghi chú có liên kết tới slide và đoạn nguồn. AI không tự thêm kết luận.
- Option C — AI tự soạn bản nháp, user kiểm tra và duyệt: Sau khi user chọn đủ highlight, AI tạo một bản nháp ghi chú có cấu trúc và gắn nguồn. User đối chiếu với slide, sửa hoặc xóa từng ý rồi quyết định xác nhận.

Chi tiết ở [three-option-design-sheet.md](three-option-design-sheet.md).

## 4. Đóng góp của tôi trong nhóm
- Phụ trách Option C mà cho AI soạn bản nháp, học viên kiểm tra và duyệt. Sử dụng AI để dựng prototype: tập hợp ghi chú theo chương → bài → slide, tìm kiếm, chỉnh sửa và quay lại nguồn. Học viên chọn ghi chú, yêu cầu tổng hợp, đối chiếu slide, sửa nháp rồi duyệt lưu. Dữ liệu mẫu không phải ghi chú thật của người được phỏng vấn.
- Trong thiết kế, tách tập hợp ghi chú thông thường khỏi AI tổng hợp theo yêu cầu. Học viên quyết định lưu bản tổng hợp; ghi chú gốc vẫn được giữ. Bổ sung ba đích cho chọn chữ và khoanh vùng: Ghi chú / Trợ giảng AI / Hỗ trợ coach. AI dùng mock; trao đổi coach hiện được xác nhận trong cùng trình duyệt, chưa đồng bộ server.
- Điều phối phiên thử A/B/C, ghi hành vi và lời nói vào Feedback Note, tách quan sát khỏi diễn giải. Đối chiếu bản deploy C về ghi chú, nguồn, tổng hợp và trao đổi coach; phân biệt kiểm tra chức năng với bằng chứng học viên có thể tự hoàn thành nhiệm vụ.

## 5. Prototype Feedback
- Feedback Note của phiên tôi facilitate: [prototype-feedback-note.md](prototype-feedback-note.md)
- Tổng hợp ba feedback: [group-feedback-synthesis.md](group-feedback-synthesis.md)

- Next Change: Làm rõ luồng chọn nội dung → chọn đích → tạo nháp → kiểm tra nguồn → duyệt; sửa panel bị cắt nội dung và kiểm tra lại fullscreen, chọn chữ nhiều dòng. Cho tester khác tạo bản ôn tập và tìm nguồn mà không hướng dẫn; thử coach riêng để đánh giá đúng giá trị tổng hợp của C.
- Still Unproven: Chưa biết học viên có tự tìm công cụ, phát hiện và sửa ý sai trước khi duyệt hay không; chưa đo hiệu quả ôn tập hoặc thời gian tìm nguồn so với A/B. AI mock chưa chứng minh chất lượng model thật; coach khác thiết bị, kéo thả, sơ đồ, đồng bộ hai tab và mobile chưa được kiểm tra đầy đủ

## 6. AI Support Log
[ai-support-log.md](ai-support-log.md)


## 7. Reflection về AI Support

 AI giúp  để hiện thực hóa các ý tưởng của Option C và chỉnh sửa prototype nhanh hơn. Tuy nhiên, AI từng hiểu sai thao tác khoanh vùng thành tự động hỏi trợ giảng, trong khi học viên cần được chọn lưu ghi chú, hỏi AI hoặc gửi hỗ trợ coach  cần mô tả rõ mục đích, quyền quyết định của người dùng và kiểm tra từng luồng thực tế.