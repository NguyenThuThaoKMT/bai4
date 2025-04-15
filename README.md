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

-Bảng GV:
![image](https://github.com/user-attachments/assets/5fdff4cb-1a70-448e-b14f-4d13131b42a3)

-Bảng LopSV:
![image](https://github.com/user-attachments/assets/240c762f-ff85-4f2e-83a4-e4861dafa4c7)

-Bảng Monhoc:
![image](https://github.com/user-attachments/assets/5fbccd3c-6ad3-48c4-817a-5b49007a9e27)

-Bảng Phonghoc:
![image](https://github.com/user-attachments/assets/be39fd5d-4298-4bdc-8726-e6f4f93094c3)

-Bảng Thoigian:
![image](https://github.com/user-attachments/assets/69c3f6a9-460e-4509-aa8b-80471c5275ee)

-Bảng Lichday:
![image](https://github.com/user-attachments/assets/6b77daaa-fb00-4b7c-9e5d-b2dcffdde27d)

liên kết khóa phụ

![image](https://github.com/user-attachments/assets/6c79d00d-2446-4bc4-aced-0c4cb2d246ce)

ta có sơ đồ liên kết sau:

![image](https://github.com/user-attachments/assets/ecdcf857-00be-428c-8410-00edd1ba9b00)

thêm dữ liệu cho các bảng:
+ Bảng GV:
  
  ![image](https://github.com/user-attachments/assets/8aba6ca9-c58d-48e5-82e5-f2d062dff7b2)

+ Bảng LopSV:

  ![image](https://github.com/user-attachments/assets/1140b310-2ed9-4d74-98f6-f748ae59d5b5)

+ Bảng MonHoc:

  ![image](https://github.com/user-attachments/assets/b0464fa8-84b0-44ee-895a-c1db966fdfe5)

+ Bảng PhongHoc:

  ![image](https://github.com/user-attachments/assets/41363614-8564-48a4-bf00-c75f268e2de2)

+ Bảng ThoiGian:

  
![image](https://github.com/user-attachments/assets/96285ec8-61cd-4462-9064-e937aa61bde3)

+ Bảng LichDay:

![image](https://github.com/user-attachments/assets/8c88647a-110c-4684-bfb2-a8f21e38a90c)


tạo query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra:

![image](https://github.com/user-attachments/assets/0bc2a8d0-c5b6-4dc1-b986-0dbf6712830f)
