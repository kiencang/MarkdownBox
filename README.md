# MarkdownBox
System Instructions dịch thuật cho tài liệu khoa học dùng ngay trong Playground của công cụ AI. File cần dịch có thể ở bất cứ định dạng nào (PDF, Markdown, DOCX, TXT, v.v..).

Bản dịch trả về định dạng markdown hiển thị ngay trên trình duyệt người dùng. 

Đầu ra là định dạng markdown có nhiều ưu thế:
- Tiết kiệm token hơn, hệ quả kéo theo là dịch được dài hơn với cùng trần đầu ra (cỡ 65 ngàn token cho đa số model) và dịch nhanh hơn với cùng văn bản;
- Markdown vẫn đảm bảo cấu trúc được dữ liệu và định dạng cơ bản, ví dụ như bảng biểu, bôi đậm, in nghiêng chứ không bị mất định dạng như văn bản thuần;
- Ít lỗi hơn, vì mã markdown rất đơn giản;
- Hiển thị được ngay trên giao diện người dùng, không cần phải copy kết quả, lưu lại rồi mới xem được.

Bạn chỉ việc copy SI này và đưa vào System Instructions trong Playground: https://github.com/kiencang/MarkdownBox/blob/main/scientific_system_instructions.md

## Ví dụ
Bạn có thể thử với Playground của Gemini: https://aistudio.google.com/prompts/new_chat

Nhìn sang bên phải sẽ thấy System instructions (SI), hãy click vào đặt tên cho SI và copy SI ở đường link trên vào để thiết lập chỉ thị hệ thống (SI) cho phiên làm việc hiện tại của bạn. Từ lần sau mỗi lần làm việc với AI bạn chỉ cần chọn lại SI mà bạn muốn từ danh sách đã lưu.

Một số tùy chọn:
- Thinking Level: Nên để là High để AI suy nghĩ sâu hơn;
- Các tùy chọn khác để như mặc định;
