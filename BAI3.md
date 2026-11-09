
**1. Input:**

-   AI đưa lệnh sửa lỗi "Path not found" khi cài Python.
-   Rủi ro: AI Hallucination, bịa lệnh, sai hệ điều hành, lệnh can thiệp sâu hệ thống.

**2. Process - Kiểm chứng:**

-   Tách lệnh: có `rm -rf`, `del`, `sudo`, `reg delete`, link lạ thì dừng.
-   Tìm: `site:stackoverflow.com "Path not found" python` + tên lệnh.
-   Đối chiếu: `site:python.org` hoặc `site:docs.python.org`.
-   Không thấy ở 2 nguồn trên = không an toàn.

**3. Output:**

-   **An toàn:** Có trên StackOverflow nhiều vote + trang chủ, chỉ sửa PATH, không xóa file hệ thống.
-   **Không an toàn:** Không tìm thấy, hoặc có lệnh xóa / sửa sâu. Không chạy.

**Prompt hỏi ngược lại AI:**

-  Giải thích lệnh này làm gì, từng tham số tác dụng gì, có xóa / sửa file hệ thống không, có an toàn trên máy tôi không, có cách an toàn hơn không cần Admin không. Cho link docs.python.org hoặc StackOverflow để tôi kiểm chứng. Nếu không giải thích được, đưa cách sửa thủ công.
