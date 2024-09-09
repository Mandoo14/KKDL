# Tên dự án: Phân loại vỏ cây bằng thuật toán Random Forest ( Rừng cây ngẫu nhiên)
## Giới thiệu về dự án:

### Mục tiêu:
        Dự án này nhằm xây dựng một mô hình phân loại vỏ cây dựa trên thuật toán Random Forest. Mô hình được huấn luyện trên một tập dữ liệu gồm các hình ảnh vỏ cây với nhãn tương ứng. Sau khi huấn luyện, mô hình         có khả năng dự đoán loại vỏ cây của một hình ảnh mới.

### Dữ liệu: 
        Photos of tree bark from Quebec – BarkNet
#### Nguồn: 
        Kaggle
#### Nội dung: 
        Bộ dữ liệu vỏ cây của Quebec, được gọi là BarkNet, là một kho dữ liệu mở được 
        cấp phép bởi MIT. Nó bao gồm các bức ảnh vỏ cây có độ phân giải cao, được 
        thu thập từ nhiều loài cây khác nhau. Những bức ảnh này được lưu trữ bởi Khoa 
        ‘Khoa học Rừng và Gỗ tại Đại học Laval’ ở Quebec. Bộ dữ liệu này hữu ích cho 
        các nhà nghiên cứu và sinh viên, cho tất cả những ai quan tâm đến lâm nghiệp 
        và sinh thái học, giúp họ dễ dàng nhận dạng các loại vỏ cây và tiến hành các 
        nghiên cứu liên quan đến đặc điểm vỏ cây.
#### Kích thước: 
         Kích thước dữ liệu gốc là 31,5 GB (23.528 ảnh) bao gồm 12 class tương ứng với 
        23 loại vỏ cây khác nhau.
        • Trong nghiên cứu này đã lấy ra 3 class từ Dataset gốc. Các hình ảnh 
        được lấy từ 3 class khác nhau: 
            ERS: "Cây phong đường" với 1911 ảnh. 
            CHR: “Sồi đỏ phương bắc” với 2724 ảnh. 
            MEL: "Tamarack" với 1874 ảnh. 
        • Với lượng hình ảnh tổng cộng 6509 ảnh do về mặt hạn chế dung lượng. Dataset 
         bao gồm Train (4557), Valid (1302), Test (650).  
        • Kích thước: 10,3 GB 
        

### Quy trình thực hiện

#### Thu thập dữ liệu: Thu thập một tập dữ liệu lớn các hình ảnh vỏ cây với nhãn tương ứng 
#### Tiền xử lý dữ liệu:
    - Đọc hình ảnh: Đọc các hình ảnh từ thư mục dữ liệu.
    - Chuyển đổi: Chuyển đổi hình ảnh thành ma trận số.
    - Kiểm tra: Kiểm tra ảnh trước khi đi vào huấn luyện : ảnh mờ , hỏng , hay vật thể không sát định.
    - Resize và Normalized : Chuyển ảnh về cùng 1 kích thước và chuẩn hóa ảnh 
    - Trích xuất đặc trưng: Trích xuất các đặc trưng hình ảnh
    - Cân bằng dữ liệu: cân bằng dữ liệu bằng Smote 
#### Huấn luyện mô hình:
    - Xây dựng mô hình: Xây dựng mô hình Random Forest với các siêu tham số phù hợp.
    - Huấn luyện: Huấn luyện mô hình trên tập huấn luyện

#### Đánh giá mô hình:
    - Đánh giá trên tập kiểm tra: Đánh giá độ chính xác của mô hình trên tập kiểm tra.
    - Dự đoán: Sử dụng mô hình đã huấn luyện để dự đoán nhãn của một hình ảnh mới.

#### Kết quả
    - Độ chính xác: Mô hình đạt được độ chính xác 83% trên tập kiểm tra.

#### Cải thiện trong tương lai
    - Tăng cường dữ liệu: Thu thập thêm dữ liệu để cải thiện độ chính xác của mô hình.
    - Thử nghiệm các mô hình khác: So sánh kết quả với các thuật toán khác như SVM, Neural Network.
    - Điều chỉnh siêu tham số: Tìm kiếm các giá trị siêu tham số tối ưu cho mô hình Random Forest.

#### Ứng dụng
    - Mô hình này có thể được ứng dụng trong các lĩnh vực như:

      Nông nghiệp: Phân loại các loại cây trồng dựa trên hình ảnh lá.
      Y tế: Phân loại các loại tế bào ung thư dựa trên hình ảnh hiển vi.
#### Liên hệ: 
  Email: khuean14112003@gmail.com
      
    
    
