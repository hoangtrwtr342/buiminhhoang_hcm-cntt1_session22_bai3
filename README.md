# Bài 3 : Sử dụng AI an toàn khi xử lý lỗi phần mềm


## Ràng buộc & Bẫy dữ liệu 

- Hiện tượng AI Hallucination : hiện tượng này thể hiện hành động của AI đưa ra không thật và không phù hợp với hệ điệu hành
- Hiện tượng này xuất hiện khi người hỏi đưa ra một dữ liệu chung chung không có bối cảnh hiện tượng hay là hệ điều hành thật . Từ đó dẫn tới AI đưa ra câu trả lời chung chung không rõ đúng sai hay đúng với hệ điều hành , và đưa ra những câu lệnh có thể anh hưởng sâu đến hệ thốn

## Mô hình IPO 

- Input (đầu vào ) : Đưa AI câu hỏi và nhận lại một câu trả lời của AI không rõ tính đúng sai

- process (Kiểm chứng) : Dùng lệnh lên những diễn đàn lớn như stackoverflow hoặc github nhờ mọi người kiểm chứng xem liệu dòng lệnh trên liệu có an toàn , có gây sự cố gì cho máy tính hay không

- Output (đầu ra) : Ta chia thành 2 phần an toàn/không an toàn
    - An toàn : Dòng lệnh trên an toàn thì ta sẽ chạy nó nhưng vẫn phải cẩn thận 
    - Không an toàn : thì ta có thể lên những diễn đàn để tìm những lỗi trên rồi sửa nó dựa trên , lỗi đó đã được sửa và công nhận

## Thiết kế promt chuẩn cho AI 

1. Context ( Bối cảnh môi trường )
  - Báo cáo rõ hệ điều hành hoặc ứng dụng đang chạy cho AI
2. Expected ( Hành vy mong muốn )
  -  Mô tả mục tiêu hoặc thao tác mong muốn thực hiện
3. Actual ( Hành động mong muốn )
  -  Trình bày chi tiết hiện tượng bất thường thực tế phát sinh
4. Log & screenshot
  - Copy nguyên văn dòng chữ thông báo lỗi tiếng Anh và đính kèm 01 tấm **Screenshot** sắc nét.
