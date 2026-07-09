## 📖 Data Dictionary

**Dataset Source:** [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

**Context:** 
- Tập dữ liệu cung cấp thông tin chi tiết về khách hàng hỗ trợ doanh nghiệp phân tích.

- Tìm hiểu hành vi và phân khúc người dùng để tối ưu hóa chiến lược sản phẩm và tiếp thị thay vì tiếp cận đại trà.

### 🧑‍🤝‍🧑 Customer Demographics

| Feature | Description |
| :--- | :--- |
| `Education` | Trình độ học vấn của khách hàng. |
| `Marital_Status` | Tình trạng hôn nhân của khách hàng. |
| `Income` | Thu nhập hộ gia đình hàng năm của khách hàng. |
| `Kidhome` | Số lượng trẻ nhỏ trong hộ gia đình. |
| `Teenhome` | Số lượng thanh thiếu niên trong hộ gia đình. |
| `Dt_Customer` | Ngày khách hàng trở thành khách hàng của công ty. |
| `Recency` | Số ngày kể từ lần mua hàng gần nhất. |
| `Complain` | `1` có khiếu nại, `0` nếu không. |

### 🛒 Behaviour 

| Feature | Description |
| :---| :--- |
| `MntWines` | Tổng số tiền chi tiêu cho mặt hàng Rượu vang. |
| `MntFruits` | Tổng số tiền chi tiêu cho mặt hàng Trái cây. |
| `MntMeatProducts` | Tổng số tiền chi tiêu cho mặt hàng Thịt. |
| `MntFishProducts` | Tổng số tiền chi tiêu cho mặt hàng Cá. |
| `MntSweetProducts` | Tổng số tiền chi tiêu cho mặt hàng Bánh kẹo/Đồ ngọt. |
| `MntGoldProds` | Tổng số tiền chi tiêu cho mặt hàng Vàng/Trang sức. |

### 🏷️ Campaign Response

| Feature | Description |
| :--- | :--- |
| `NumDealsPurchases` | Số lần mua hàng có sử dụng mã giảm giá. |
| `AcceptedCmp1` | `1` chấp nhận ưu đãi trong chiến dịch thứ 1, `0` nếu không. |
| `AcceptedCmp2` | `1` chấp nhận ưu đãi trong chiến dịch thứ 2, `0` nếu không. |
| `AcceptedCmp3` | `1` chấp nhận ưu đãi trong chiến dịch thứ 3, `0` nếu không. |
| `AcceptedCmp4` | `1` chấp nhận ưu đãi trong chiến dịch thứ 4, `0` nếu không. |
| `AcceptedCmp5` | `1` chấp nhận ưu đãi trong chiến dịch thứ 5, `0` nếu không. |
| `Response` | `1` chấp nhận ưu đãi trong chiến dịch gần nhất, `0` nếu không. |

### 🏪 Place 

| Feature | Description |
| :--- | :--- |
| `NumWebPurchases` | Số lần mua hàng thông qua Website. |
| `NumCatalogPurchases` | Số lần mua hàng thông qua Catalogue. |
| `NumStorePurchases` | Số lần mua hàng thông qua cửa hàng trực tiếp. |
