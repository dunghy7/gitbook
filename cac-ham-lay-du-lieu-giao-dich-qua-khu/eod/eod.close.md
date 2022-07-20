---
description: >-
  Lấy giá đóng cửa trong các ngày giao dịch của 1 mã hoặc index trong 1 khoảng
  thời gian
---

# EOD.Close

### Cú pháp

> `=EOD.Close("Mã chứng khoán", "Ngày bắt đầu", "Ngày kết thúc")`

Tham số:

* **Mã chứng khoán**: Mã chứng khoán cần lấy thông tin hoặc index (VNINDEX, HNXINDEX, UPINDEX, VN30, HNX30,...).
* **Ngày bắt đầu**: Ngày bắt đầu lấy dữ liệu, định dạng _dd/MM/yyyy_.
* **Ngày kết thúc**: Ngày kết thúc lấy dữ liệu, định dạng _dd/MM/yyyy_.

### Giá trị trả về

Một chuỗi các giá trị trong đó mỗi phần tử là giá đóng cửa ứng với 1 ngày giao dịch trong khoảng thời gian
