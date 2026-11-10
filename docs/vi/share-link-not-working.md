# Link chia sẻ Baidu Pan không mở được: ý nghĩa của từng thông báo

Bạn mở một liên kết `pan.baidu.com` và chỉ thấy một dòng thông báo ngắn bằng tiếng Trung thay vì danh sách tệp. Trang này giải thích thông báo đó có nghĩa gì và bạn có thể làm gì.

## Trước tiên, kiểm tra địa chỉ

Một liên kết bình thường có dạng `https://pan.baidu.com/s/1…`, sau số `1` là một dãy dài chữ cái và chữ số. Sau khi mở, trình duyệt có thể hiển thị `https://pan.baidu.com/share/init?surl=…`. Đó vẫn là cùng một liên kết chia sẻ.

Nếu liên kết bị cắt mất một đoạn khi sao chép, nó sẽ không mở được. Hãy sao chép lại từ tin nhắn gốc, lấy đến tận ký tự cuối cùng.

## Trang đang báo cho bạn điều gì

| Bạn thấy gì | Ý nghĩa | Ai khắc phục được |
| --- | --- | --- |
| Một ô yêu cầu nhập bốn ký tự | Liên kết chia sẻ được bảo vệ. Bạn cần [mã truy cập](extraction-code.md) | Bạn, với mã lấy từ chủ sở hữu |
| Thông báo rằng bạn đến muộn và liên kết chia sẻ đã bị hủy | Chủ sở hữu đã ngừng chia sẻ, hoặc Baidu đã gỡ các tệp | Chủ sở hữu |
| Thông báo về hành vi vi phạm hoặc nội dung bị cấm | Baidu đã chặn liên kết chia sẻ | Không ai cả: liên kết vẫn tiếp tục bị chặn |
| Danh sách tệp kèm ghi chú rằng một số tệp đã bị lọc bỏ | Một phần nội dung vi phạm quy định của Baidu và bị ẩn đi | Chủ sở hữu |
| Thông báo rằng liên kết chia sẻ không còn hiệu lực | Liên kết chia sẻ đã hết hạn | Chủ sở hữu |

Tính năng dịch của trình duyệt giúp bạn phân biệt các thông báo này.

## Nên làm gì

- **Mã bị từ chối:** so từng ký tự với tin nhắn gốc. Xem [Mã truy cập](extraction-code.md).
- **Liên kết chia sẻ bị hủy hoặc hết hạn:** nhờ chủ sở hữu chia sẻ lại các tệp và gửi cho bạn liên kết cùng mã mới.
- **Liên kết chia sẻ bị chặn:** không còn gì để tải. Hãy hỏi chủ sở hữu xem các tệp có ở nơi nào khác không.

## Kiểm tra trước khi trả bất kỳ khoản nào

Thử liên kết trong [công cụ kiểm tra liên kết của PanPull](https://panpull.com/vi?utm_source=github&utm_medium=tutorial#link-checker). Việc kiểm tra miễn phí. Nếu đọc được liên kết chia sẻ, bạn sẽ thấy số tệp, tổng dung lượng và giá. Nếu không đọc được, bạn nhận thông báo lỗi và không bị tính phí gì.

Không dịch vụ nào khôi phục được liên kết chia sẻ đã bị xóa, hủy hoặc chặn. Nếu liên kết không chạy trên PanPull nhưng chủ sở hữu vẫn mở được bình thường, hãy thử lại sau một lúc: nguyên nhân có thể chỉ là tạm thời.

Đọc thêm trên blog PanPull: [Link chia sẻ Baidu không mở được: cần kiểm tra gì](https://panpull.com/vi/blog/baidu-share-unavailable-checklist?utm_source=github&utm_medium=tutorial).

---

**Bạn có liên kết Baidu? [Kiểm tra trên PanPull](https://panpull.com/vi?utm_source=github&utm_medium=tutorial#link-checker)** để xem dung lượng và giá trước. Đến 150 MB được miễn phí.

[Tất cả hướng dẫn](README.md) · [Ngôn ngữ khác](../README.md#languages)
