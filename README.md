# Dự án Phân loại bằng Mô hình KNN

## Mô tả

Dự án này sử dụng mô hình KNN (K-nearest neighbors) để phân loại dữ liệu trên hai bộ dữ liệu khác nhau: Iris và Wine. Mô hình được huấn luyện trên các đặc trưng của dữ liệu để dự đoán loại của mỗi mẫu.Nhầm để
so sánh hai mẫu đó , và đánh giá mô hình KNN phù hợp thế nào

## Bộ dữ liệu

### Iris

Bộ dữ liệu Iris chứa thông tin về ba loài hoa Iris: Iris Setosa, Iris Versicolor và Iris Virginica. Mỗi loài có 50 mẫu, với mỗi mẫu có 4 đặc trưng: chiều dài đài hoa, chiều rộng đài hoa, chiều dài cánh hoa và chiều rộng cánh hoa.

![Ví dụ về Iris flower dataset](https://machinelearningcoban.com/assets/knn/iris.png)

### Wine

Bộ dữ liệu Wine chứa thông tin về ba loại rượu: Class 0, Class 1 và Class 2. Bộ dữ liệu này có 178 mẫu và mỗi mẫu có 13 đặc trưng hóa học.

![Hình ảnh minh họa về Wine dataset](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Vietnam_Dalat_wine_%28white%29.jpg/1200px-Vietnam_Dalat_wine_%28white%29.jpg)

## Phân loại với KNN

Mô hình KNN được sử dụng để phân loại dữ liệu trên cả hai bộ dữ liệu. KNN là một mô hình học máy đơn giản nhưng mạnh mẽ, dựa vào việc tính khoảng cách giữa các điểm dữ liệu để dự đoán nhãn cho một điểm mới. 

## So sánh hiệu suất

Mô hình KNN được huấn luyện và đánh giá trên cả hai bộ dữ liệu Iris và Wine. Sau đây là kết quả đánh giá hiệu suất của mô hình trên mỗi bộ dữ liệu:
- Thứ nhất:Kích thước dữ liệu: Bộ dữ liệu Iris có 150 mẫu và 4 đặc trưng, trong khi bộ dữ liệu Wine có 178 mẫu và 13 đặc trưng. Do đó, bộ dữ liệu Wine lớn hơn Iris.
- Thứ hai Số lượng lớp: Bộ dữ liệu Iris có 3 lớp (Setosa, Versicolor, Virginica), trong khi bộ dữ liệu Wine có 3 lớp tương ứng với 3 loại rượu (1, 2, 3).
- Thứ ba: Độ phức tạp của bài toán phân loại: Do bộ dữ liệu Wine có nhiều đặc trưng hơn, việc phân loại có thể phức tạp hơn so với bộ dữ liệu Iris.
- Thứ tư: Khi train hai bộ dữ liệu vói mô hình KNN ta thấy, độ chính xác của Iris cao hơn Wine
- Kết luận: Mô hình KNN đơn giản, dễ sử dụng nhưng nó chỉ phù hợp với bộ dữ liệu nhỏ có mẫu và đặc trưng ít, còn những bộ dữ liệu lớn có mẫu và dặc trưng lơn khả năng dự đoán chính xác thấp.
## Yêu cầu

- Python 3.x
- Các thư viện Python cần thiết được liệt kê trong yeucau.txt.

## Cách sử dụng

1. Clone repository về máy của bạn: `https://github.com/taiiswibu/model_KNN.git`
2. Cài đặt các thư viện cần thiết: pip install -r yeucau.txt
3. Di chuyển vào thư mục dự án: `cd KNN`
4. Chạy notebook Jupyter hoặc các tập lệnh Python có sẵn để thực thi các tác vụ.

## Tác giả

- Tên: [Vỏ Văn Tài](https://github.com/taiiswibu)
  
#Tài liệu tham khảo
- [tài liệu tham khảo](https://machinelearningcoban.com/2017/01/08/knn/)
