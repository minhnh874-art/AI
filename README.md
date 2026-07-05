## Luồng dữ liệu
1. Nhân viên mở website checklist.
2. Nhập Flight No., Date, ATA/Chock-on và các Actual Time.
3. Bấm `Gửi Google Sheets`.
4. Apps Script ghi dữ liệu vào Google Sheets:
   - Sheet `SUMMARY`: 1 dòng tổng hợp cho mỗi Flight Date + Flight No.
   - Sheet theo ngày bay, ví dụ `2026-07-05`: chi tiết từng task của checklist.
5. Nếu gửi lại cùng Flight Date + Flight No., dữ liệu cũ cùng RecordKey được thay bằng bản mới.

