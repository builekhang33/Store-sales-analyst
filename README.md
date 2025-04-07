# Store-sales-analyst

Tổng quan
Dự báo rất quan trọng trong việc xác định mức tồn kho và việc ước tính chính xác nhu cầu hàng hóa trong tương lai luôn là một thách thức, đặc biệt là trong những siêu thị và cửa hàng tạp hóa. Nếu hàng hóa không có sẵn hoặc lượng hàng hóa sẵn có nhiều hơn nhu cầu thì tổng lợi nhuận có thể bị tổn hại. Do đó, việc dự báo doanh số bán hàng có thể rất quan trọng để đảm bảo giảm thiểu tổn thất. Ngoài ra, vấn đề trở nên phức tạp hơn khi các nhà bán lẻ thêm các địa điểm mới với nhu cầu riêng, sản phẩm mới, thị hiếu theo mùa luôn thay đổi và hoạt động tiếp thị sản phẩm không thể đoán trước.

Mục tiêu dự án
Mục tiêu của dự án này là dự báo doanh số bán sản phẩm chính xác hơn cho chuỗi siêu thị dựa trên một số tính năng nhất định.

Mục tiêu của dự án này là cố gắng dự báo doanh số bán sản phẩm dựa trên các mặt hàng, cửa hàng, giao dịch và các biến phụ thuộc khác như ngày lễ và giá dầu. Nhiệm vụ là dự đoán dự trữ sản phẩm để đảm bảo tốt hơn các cửa hàng tạp hóa làm hài lòng khách hàng bằng cách có đủ sản phẩm phù hợp vào đúng thời điểm. Sử dụng một số mô hình học máy để dự báo doanh số bán hàng như Linear Regression, Decision Tree, ExtraTreeRegressor, Gradient Boosting, Random Forest và XgBoost. Hơn nữa để tối ưu hóa kết quả, chúng tôi đã sử dụng nhận thức đa lớp (MLP: một lớp mạng thần kinh nhân tạo chuyển tiếp nguồn cấp dữ liệu) và LightGBM (khung tăng cường độ dốc sử dụng thuật toán học tập dựa trên cây). Dữ liệu có hình dạng của nhiều tệp. Đầu tiên, dữ liệu đào tạo (train.csv) về cơ bản chứa doanh số bán hàng theo ngày, cửa hàng và mặt hàng. Dữ liệu thử nghiệm (test.csv) chứa các tính năng tương tự mà không có thông tin bán hàng mà chúng tôi được giao nhiệm vụ dự đoán. Sự phân chia tàu và thử nghiệm dựa trên ngày. Ngoài ra, một số mục kiểm tra không được bao gồm trong dữ liệu tàu.

