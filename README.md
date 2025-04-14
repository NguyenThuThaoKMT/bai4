# bai4
baitap4_nguyenthuthao_k225480106060

bai tap 4: (sql server)
yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.

các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó

Gợi ý:
  sử dung tms => dữ liệu thô => tiền xử lý => dữ liệu như ý (3nf)
  tạo các bảng với struct phù hợp
  insert nhiều rows từ excel vào cửa sổ edit dữ liệu 1 table (quan sát thì sẽ làm đc)
  

deadline: 15/4/2025

-----------------------------------------------------------------------------------------
tạo các bảng và cài khóa chính cho bảng
![image](https://github.com/user-attachments/assets/dda7f9fd-60db-4372-9b0b-92795d22574c)
![image](https://github.com/user-attachments/assets/18590201-1f36-42ba-9d5b-b5194ff20f19)
![image](https://github.com/user-attachments/assets/86d3aa0b-91b1-470c-b5d2-c6e94a695bf4)
![image](https://github.com/user-attachments/assets/c92e8f9a-aaf6-439f-ad88-26c6081c95a4)
![image](https://github.com/user-attachments/assets/418a4de5-0398-485e-981e-babeea670a84)
liên kết khóa phụ
![image](https://github.com/user-attachments/assets/6c79d00d-2446-4bc4-aced-0c4cb2d246ce)
ta có sơ đồ liên kết sau:
![image](https://github.com/user-attachments/assets/ecdcf857-00be-428c-8410-00edd1ba9b00)
thêm dữ liệu cho các bảng:
