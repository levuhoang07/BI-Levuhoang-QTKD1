# BI301 – PHÂN TÍCH KHỦNG HOẢNG TẠI ZARA

## 1. Phân tích tình huống theo mô hình DIKW

### Data – Dữ liệu

Sản phẩm **Z101** là áo khoác màu đỏ, bán tại **Châu Á** qua kênh **Online**. Sản phẩm bán được **500 chiếc**, trong đó có **150 chiếc bị trả lại**. Trong các trường hợp hoàn trả, **85% liên quan đến lỗi khóa kéo**. Phản hồi nổi bật của khách hàng là: **“Khóa ngược khó kéo, dễ kẹt”**.

Các sản phẩm còn lại trong bảng có tỷ lệ hoàn trả và tỷ lệ lỗi khóa kéo thấp hơn, vì vậy Z101 là điểm bất thường cần phân tích.

### Information – Thông tin

Tỷ lệ hoàn trả của Z101:

**Return Rate = 150 / 500 × 100% = 30%**

Như vậy, Z101 có tỷ lệ hoàn trả **30%**. Đồng thời, **85% trường hợp trả lại liên quan đến khóa kéo**, cho thấy vấn đề tập trung mạnh vào một chi tiết cụ thể.

### Knowledge/Insight – Tri thức và Insight

Khi kết hợp tỷ lệ hoàn trả 30%, tỷ lệ lỗi khóa kéo 85% và phản hồi khách hàng, có thể hình thành insight rằng **thiết kế khóa kéo ngược của Z101 có khả năng không phù hợp với trải nghiệm sử dụng của khách hàng tại Châu Á**.

Dữ liệu hiện tại chưa đủ để khẳng định lỗi kỹ thuật duy nhất nằm ở bản thân khóa kéo. R&D vẫn cần kiểm tra thêm chất lượng linh kiện, cách lắp ráp và thiết kế. Tuy nhiên, khóa kéo là điểm cần ưu tiên điều tra vì đây là nguyên nhân tập trung nhất trong dữ liệu.

## 2. Nhiệm vụ 1 – Quyết định ở cấp độ Wisdom

### Quyết định 1: Xử lý lô Z101 đang tồn kho

Zara nên **tạm dừng xuất bán lô Z101 còn tồn kho tại Châu Á và kiểm tra 100% khóa kéo trước khi tiếp tục phân phối**. Những sản phẩm có lỗi hoặc nguy cơ kẹt khóa cần được sửa, thay khóa hoặc loại khỏi luồng bán hàng.

Quyết định này dựa trên tỷ lệ hoàn trả 30% và việc 85% lỗi tập trung vào khóa kéo. Nếu tiếp tục bán mà không kiểm tra, số lượng trả hàng có thể tăng thêm và ảnh hưởng đến trải nghiệm khách hàng.

### Quyết định 2: Điều chỉnh quy trình R&D

R&D nên bổ sung **bước kiểm thử trải nghiệm sử dụng và độ bền của các chi tiết chức năng như khóa kéo trước khi sản xuất hàng loạt**. Với thiết kế mới như khóa ngược, Zara nên thử nghiệm trên mẫu nhỏ, thu thập phản hồi và chỉ mở rộng sản xuất khi thiết kế đạt yêu cầu.

Dữ liệu hoàn trả theo nguyên nhân cũng cần được chuyển ngược về R&D để đội thiết kế phát hiện sớm những lỗi lặp lại.

## 3. Nhiệm vụ 2 – Phân biệt Report và BI tại Zara

### Report – Báo cáo

Report chủ yếu trả lời câu hỏi **“Điều gì đã xảy ra?”**. Trong tình huống này, các hành động mang tính Report gồm:

- Ghi nhận Z101 bán 500 sản phẩm và trả 150 sản phẩm.
- Tính tỷ lệ hoàn trả 30%.
- Thống kê 85% trường hợp trả liên quan đến khóa kéo.
- Tổng hợp phản hồi của khách hàng.

Report giúp nhà quản lý nhìn thấy hiện trạng nhưng chưa trực tiếp chỉ ra nên hành động như thế nào.

### BI – Trí tuệ doanh nghiệp

BI sử dụng dữ liệu để **phát hiện bất thường, tìm mối liên hệ, tạo insight và hỗ trợ ra quyết định**.

Trong tình huống Z101, giá trị BI xuất hiện khi Zara:

- So sánh Z101 với các sản phẩm khác để nhận diện mức hoàn trả bất thường.
- Kết hợp Return Rate, tỷ lệ lỗi khóa kéo và phản hồi khách hàng để xác định điểm nghi vấn chính.
- Đề xuất kiểm tra tồn kho và sửa sản phẩm trước khi bán tiếp.
- Đưa dữ liệu hoàn trả quay lại quy trình R&D để cải thiện thiết kế tương lai.

Như vậy, **Report cung cấp số liệu**, còn **BI biến số liệu thành insight và hành động quản trị**.

## 4. Kết luận

Trong tình huống Z101, dữ liệu chỉ tạo ra giá trị khi được chuyển qua các cấp độ DIKW. Zara đi từ dữ liệu bán và trả hàng đến thông tin về tỷ lệ hoàn trả, hình thành insight về khóa kéo và cuối cùng đưa ra quyết định xử lý tồn kho cũng như cải tiến R&D. Đây là sự khác biệt giữa việc chỉ làm báo cáo và ứng dụng Business Intelligence trong quản trị.
