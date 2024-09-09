# Tên dự án: Phân loại vỏ cây bằng thuật toán Random Forest ( Rừng cây ngẫu nhiên)
## Giới thiệu về dự án:
### Dự án này nhằm xây dựng một mô hình phân loại vỏ cây dựa trên thuật toán Random Forest. Mô hình được huấn luyện trên một tập dữ liệu gồm các hình ảnh vỏ cây với nhãn tương ứng. Sau khi huấn luyện, mô hình có khả năng dự đoán loại vỏ cây của một hình ảnh mới chưa từng thấy

### Mục tiêu:
#### Phân loại ác hỉnh ảnh vỏ cây được đưa vào thuật toán 

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
      
    
    
