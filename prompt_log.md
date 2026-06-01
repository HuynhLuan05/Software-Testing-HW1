# PROMPT LOG

* **Họ và tên:** **Huỳnh Sĩ Luân**
* **MSSV:** **23127086**

---

## Prompt 1: Đọc và tóm tắt yêu cầu đề bài
* **Công cụ sử dụng:** Gemini 3.5 Flash (Medium)
* **Thời gian thực hiện:** 09:30 29/05/2026
* **Nội dung Prompt:**
  > Đọc nội dung tệp docx yêu cầu bài tập và tóm tắt các yêu cầu chính mà sinh viên cần thực hiện, các file cần nộp cũng như quy chế tuân thủ AI của học phần này.
* **Kết quả phản hồi của AI:**
  AI đọc và liệt kê chi tiết 3 yêu cầu cốt lõi của bài tập HW01 (10 tin tuyển dụng QA/QC, 20 lỗi phần mềm, thiết kế và chạy thử 15 test cases máy lạnh), các biểu mẫu AI bắt buộc đính kèm (AI-02, AI-03, AI-05, AI-06) và quy cách đóng gói file nộp bài (.zip).

---

## Prompt 2: Tạo sơ đồ tư duy vai trò QA/QC (ISTQB v4.0)
* **Công cụ sử dụng:** Gemini 3.5 Flash (Medium)
* **Thời gian thực hiện:** 18:15 29/05/2026
* **Nội dung Prompt:**
  > Hãy vẽ một sơ đồ tư duy dạng cây bằng mã Mermaid mô tả vai trò QA/QC và các hoạt động kiểm thử theo chuẩn ISTQB CTFL v4.0.
* **Kết quả phản hồi của AI:**
  AI sinh ra sơ đồ Mermaid có các lỗi sai: (1) xếp Debugging là hoạt động của Tester trong nhánh Thực thi, (2) xếp Static Testing làm nhánh con của Dynamic Testing, (3) giới hạn Regression Testing chỉ ở Unit Level.

---

## Prompt 3: Thiết kế test cases cho thiết bị vật lý
* **Công cụ sử dụng:** Gemini 3.5 Flash (Medium)
* **Thời gian thực hiện:** 21:23 30/05/2026
* **Nội dung Prompt:**
  > Hãy thiết kế 12 test cases cơ bản cho một máy lạnh gia dụng dựa trên các phím chức năng của remote điều khiển. Trình bày dưới dạng bảng Markdown với các cột: Mã TC, Mục tiêu, Dữ liệu đầu vào, Các bước thực hiện, Kết quả kỳ vọng.
* **Kết quả phản hồi của AI:**
  AI sinh ra bảng 12 test cases từ TC01 đến TC12 bao phủ các phím chức năng cơ bản của remote. Tuy nhiên thiếu kết quả thực tế và thiếu hoàn toàn các kịch bản kiểm thử biên vật lý (giới hạn nhiệt độ, dội phím......).

---

## Prompt 4: Tìm kiếm/Phân tích thông tin lỗi phần mềm
* **Công cụ sử dụng:** Gemini 3.5 Flash (Medium)
* **Thời gian thực hiện:** 13:19 31/05/2026
* **Nội dung Prompt:**
  > Hãy lập danh sách 20 sự cố/lỗi phần mềm nổi tiếng xảy ra trong giai đoạn 2022–2026, trong đó có ít nhất 5 lỗi liên quan đến AI/LLM (ảo giác, prompt injection, thiên kiến). Với mỗi lỗi cần có: tên sự cố, đường link nguồn, mô tả lỗi, mức độ nghiêm trọng, hậu quả và giải pháp khắc phục.
* **Kết quả phản hồi của AI:**
  AI trả về danh sách 20 sự cố có thông tin khá đầy đủ nhưng các đường link nguồn tham khảo đều là link ảo giác — khi nhấn vào thực tế đều báo lỗi 404 Not Found. Sinh viên đã tự tìm kiếm lại và thay thế bằng các bài báo chính thống có đường dẫn hoạt động thực tế.
