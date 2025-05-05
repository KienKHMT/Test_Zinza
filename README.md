# Test_Zinza
Dự án này triển khai hai cách tiếp cận để gộp các đơn hàng theo địa chỉ giao nhằm tối ưu chi phí vận chuyển. Hai cách tiếp cận được sử dụng là:

1. **Sử dụng từ điển (Dictionary)**: Nhóm đơn hàng theo địa chỉ bằng cách sử dụng cấu trúc dữ liệu từ điển.
2. **Sử dụng danh sách và lặp **: Duyệt danh sách đơn hàng để tìm và gộp các đơn hàng có cùng địa chỉ.

## So Sánh Hai Cách Tiếp Cận

Bảng dưới đây so sánh hai cách tiếp cận dựa trên ba tiêu chí: độ rõ ràng của code, hiệu năng, và khả năng mở rộng.

| Tiêu chí             | Cách tiếp cận 1 (Từ điển)                                      | Cách tiếp cận 2 (Danh sách và lặp)                          |
|---------------------|-------------------------------------------------------------|-----------------------------------------------------------|
| **Độ rõ ràng**      | Rõ ràng, cấu trúc tốt, nhưng hơi phức tạp cho người mới.     | Rất đơn giản, dễ hiểu, nhưng có thể lặp lại và lộn xộn.    |
| **Hiệu năng**       | O(n), hiệu quả với dữ liệu lớn.                             | O(n²), kém hiệu quả với dữ liệu lớn.                      |
| **Khả năng mở rộng**| Linh hoạt, dễ thêm tính năng mới, phù hợp hệ thống lớn.      | Hạn chế, phù hợp hệ thống nhỏ hoặc đơn giản.               |
