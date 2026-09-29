# BÀI TẬP VỀ NHÀ BI301 – PHÂN TÍCH DỮ LIỆU KINH DOANH TẠI ZARA

## 1. Bối cảnh

Zara là thương hiệu thời trang nhanh hoạt động trên nhiều thị trường. Trong tình huống của bài tập, bộ phận R&D phát hiện sản phẩm áo khoác mã **Z101** tại **Châu Á** có tỷ lệ hoàn trả bất thường. Phản hồi khách hàng cho biết sản phẩm gặp vấn đề **“khóa ngược dễ kẹt”**.

Với vai trò chuyên gia dữ liệu, nhiệm vụ là trích xuất dữ liệu liên quan đến Z101 từ bảng số liệu thô, sau đó tính tỷ lệ hoàn trả để chuyển dữ liệu ban đầu thành thông tin có ý nghĩa phục vụ phân tích.

## 2. Nhiệm vụ 1 – Trích xuất Data

Từ bảng dữ liệu đầu vào, sản phẩm Z101 có các thông tin:

- **Mã sản phẩm:** Z101
- **Danh mục:** Áo khoác
- **Màu sắc:** Đỏ
- **Khu vực:** Châu Á
- **Số lượng bán:** 500
- **Số lượng trả:** 150
- **Phản hồi:** Khóa ngược dễ kẹt

Theo yêu cầu của bài tập, hai dữ liệu chính cần trích xuất là:

- **Số lượng bán của Z101 = 500 sản phẩm**
- **Số lượng trả của Z101 = 150 sản phẩm**

Hai con số này là dữ liệu thô. Tuy nhiên, nếu chỉ nhìn vào 150 sản phẩm bị trả thì chưa đủ để đánh giá mức độ nghiêm trọng, vì cần so sánh số lượng trả với tổng số lượng đã bán.

## 3. Nhiệm vụ 2 – Tính toán Information

Tỷ lệ hoàn trả được tính theo công thức:

**Return Rate = (Số lượng trả / Số lượng bán) × 100%**

Áp dụng dữ liệu của Z101:

**Return Rate = (150 / 500) × 100% = 30%**

Như vậy, **tỷ lệ hoàn trả của sản phẩm Z101 là 30%**.

Điều này có nghĩa là cứ 100 sản phẩm Z101 bán ra thì có khoảng 30 sản phẩm bị khách hàng trả lại. Tỷ lệ 30% phản ánh rõ hơn mức độ của vấn đề so với việc chỉ quan sát con số tuyệt đối 150 sản phẩm hoàn trả.

## 4. Nhận xét

Dữ liệu cho thấy Z101 bán được 500 sản phẩm nhưng có 150 sản phẩm bị trả. Đồng thời, phản hồi được ghi nhận liên quan trực tiếp đến khóa kéo bị kẹt. Vì vậy, bộ phận R&D nên ưu tiên kiểm tra chất lượng khóa kéo của lô Z101 đang phân phối tại Châu Á.

Tuy nhiên, bộ dữ liệu chỉ cung cấp một dòng thông tin về Z101 và không có dữ liệu lịch sử hoặc dữ liệu của các lô khác. Do đó, chưa thể khẳng định toàn bộ trường hợp hoàn trả đều do lỗi khóa kéo. Kết quả hiện tại chỉ cho thấy Z101 có **Return Rate 30%** và có dấu hiệu chất lượng cần được kiểm tra thêm.

## 5. Kết luận

Qua quá trình xử lý, dữ liệu thô của Z101 đã được chuyển thành thông tin phục vụ phân tích kinh doanh. Kết quả chính là **500 sản phẩm bán ra, 150 sản phẩm bị trả và tỷ lệ hoàn trả 30%**.

Thông tin này giúp Zara nhận diện nhanh mức độ bất thường của sản phẩm và cung cấp cơ sở ban đầu để bộ phận R&D kiểm tra nguyên nhân, đánh giá chất lượng lô hàng và đề xuất biện pháp xử lý phù hợp.
