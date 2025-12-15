# khoa_hoc_nhan_thuc
unet_2d_for brats
README
📌 Giới thiệu

Repository này chứa mã nguồn huấn luyện và mô hình đã được train cho bài toán phân đoạn khối u não bằng unet 2d.

📂 Nội dung chính
1. Xem code train

Nếu bạn muốn xem toàn bộ quá trình huấn luyện mô hình, vui lòng mở notebook:

diceloss-cce.ipynb


Notebook này bao gồm:

Tiền xử lý dữ liệu

Định nghĩa mô hình

Hàm loss (Dice Loss + Categorical Cross Entropy)

Quá trình train và đánh giá

2. Tải model để chạy thử

Nếu bạn không muốn train lại từ đầu mà chỉ muốn tải model đã huấn luyện sẵn để chạy thử:

Mở file:

model.txt


Trong file có link Google Drive để tải model đã train.

Sau khi tải về, đặt model vào đúng thư mục theo hướng dẫn trong code.

⚙️ Yêu cầu môi trường

Python 3.x

TensorFlow / Keras

NumPy, OpenCV, Matplotlib
(có thể bổ sung thêm nếu cần)

❓ Ghi chú

Notebook diceloss-cce.ipynb được dùng cho mục đích nghiên cứu và thử nghiệm.

Model được cung cấp chỉ để inference / test, không khuyến khích dùng cho mục đích thương mại.
