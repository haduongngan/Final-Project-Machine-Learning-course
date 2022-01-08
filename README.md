# Giới thiệu bài toán

Ngày nay, cùng với sự phát triển của công nghệ, rất nhiều các tác vụ đã được trực tuyến hoá, mang lại sự tiện lợi và giúp tiết kiệm đáng kể thời gian, công sức của con người. Trong bối cảnh đó, các trang thương mại điện tử ngày càng phát triển và thu hút nhiều người sử dụng, thay đổi dần dần thói quen mua sắm của con người. Xu hướng đó đặt các trang web mua sắm trước sự thúc đẩy phát triển các thuật toán vận hành để tăng sự hài lòng của người dùng. 

Năm 2016, Home Depot mong muốn các Kagglers giúp họ cải thiện trải nghiệm mua sắm của khách hàng bằng cách phát triển **một mô hình có thể dự đoán chính xác mức độ liên quan của kết quả tìm kiếm** trên trang web [homedepot.com](https://www.homedepot.com/). Mức độ liên quan của tìm kiếm là một thước đo ngầm mà Home Depot sử dụng để đánh giá độ nhanh chóng mà trang web này có thể đưa khách hàng đến với sản phẩm phù hợp nhu cầu của họ. Cụ thể, mức độ liên quan được chỉ định cho mỗi cặp **‘cụm từ tìm kiếm của khách hàng’** và **‘kết quả sản phẩm mà trang web trả về’.**

**Dữ liệu đầu vào:** Dữ liệu đầu vào của mô hình dự đoán là các cặp ‘cụm từ tìm kiếm’ - ‘sản phẩm trả về tương ứng’.

**Đầu ra mong muốn:** Với từng dữ liệu cặp như vậy, Home Depot mong muốn biết được độ liên quan giữa ‘cụm từ tìm kiếm’ đó và ‘sản phẩm trả về’. Mức độ liên quan là một số trong khoảng từ 1 (ứng với không liên quan) đến 3 (mang ý nghĩa là có liên quan cao)

# Các file trong git
Các tệp và thư mục trong git này bao gồm:
- File chứa code ML-final-pj.ipynb
- Các file chứa dữ liệu .csv (bao gồm dữ liệu cuộc thi cung cấp và dữ liệu ghi ra lưu lại trong quá trình cài đặt, xử lý dữ liệu) (thiếu file attributes và descriptions do kích thước quá lớn khó đẩy lên git. Dữ liệu có thể được tìm thấy ở https://www.kaggle.com/c/home-depot-product-search-relevance/data)
- Thư mục model chứa model đã được huấn luyện và lưu 
