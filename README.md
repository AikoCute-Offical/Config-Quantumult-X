Bài viết dưới đây hướng dẫn cách chặn quảng cáo trong ứng dụng trên hệ điều hành iOS bằng Quantumult X

1. [Giới thiệu](https://github.com/bigdargon/hostsVN/wiki/Quantumult-X#gi%E1%BB%9Bi-thi%E1%BB%87u)
2. [Chuẩn bị](https://github.com/bigdargon/hostsVN/wiki/Quantumult-X#chu%E1%BA%A9n-b%E1%BB%8B)
3. [Thêm cấu hình vào Quantumult X](https://github.com/bigdargon/hostsVN/wiki/Quantumult-X#th%C3%AAm-c%E1%BA%A5u-h%C3%ACnh-v%C3%A0o-quantumult-x)
4. [Bật Always On](https://github.com/bigdargon/hostsVN/wiki/Quantumult-X#b%E1%BA%ADt-always-on)
5. [Đồng bộ](https://github.com/bigdargon/hostsVN/wiki/Quantumult-X#%C4%90%E1%BB%93ng-b%E1%BB%99)
6. [Bật tính năng HTTPS](https://github.com/bigdargon/hostsVN/wiki/Quantumult-X#b%E1%BA%ADt-t%C3%ADnh-n%C4%83ng-https)
7. [Bật VPN](https://github.com/bigdargon/hostsVN/wiki/Quantumult-X#b%E1%BA%ADt-vpn)
8. [Cập nhật cấu hình](https://github.com/bigdargon/hostsVN/wiki/Quantumult-X#c%E1%BA%ADp-nh%E1%BA%ADt-c%E1%BA%A5u-h%C3%ACnh)
9. [Báo lỗi](https://github.com/bigdargon/hostsVN/wiki/Quantumult-X#b%C3%A1o-l%E1%BB%97i)

# Giới thiệu

Tải ứng dụng: https://itunes.apple.com/app/quantumult-x/id1443988620?mt=8

![](https://is2-ssl.mzstatic.com/image/thumb/Purple113/v4/65/04/d1/6504d15f-eb22-526e-1055-352290c0feb9/pr_source.png/300x0w.jpg) ![](https://is4-ssl.mzstatic.com/image/thumb/Purple123/v4/e2/30/68/e230680f-1bff-498a-8cee-52a231c637c7/pr_source.png/300x0w.jpg)

Lưu ý:
* Đây là ứng dụng tốn phí để tải về với mức giá ~109.000 VND~ `179.000 VND`
* Với tính năng `HTTPS` giúp việc lọc quảng cáo ở các ứng dụng tốt hơn nhưng bạn sẽ đánh đổi thời lượng pin sẽ ngắn lại (do CPU liên tục phân giải HTTPS). Nhưng nếu bạn tắt tính năng `HTTPS` sẽ không ảnh hưởng
* Sau mỗi lần khởi động, VPN tự động bật nhờ tính năng `Always On`.

## Chuẩn bị

Trước khi bắt đầu cài đặt, bạn cần phải thực hiện **Opt-out** để giới hạn quảng cáo trên thiết bị của bạn. Thực hiện theo bài viết [hướng dẫn Opt-out này.](https://github.com/bigdargon/hostsVN/wiki/Opt-out)

## Thêm cấu hình vào Quantumult X

Bước 1: Tại màn hình chính, chọn icon được đánh dấu như hình

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B01.jpg)

Bước 2: Chọn `Download`

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B02.jpg)

Bước 3: Dán đường dẫn cấu hình https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hostsVN-quantumultX.conf vào ô `url`

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B03.jpg)

Nhấn `Save` để lưu cấu hình (nếu là lần đầu sẽ có popup một số lưu ý, nhấn `OK` để bỏ qua)

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B03-1.jpg)

# Bật Always On

Bước 4: Nhấn vào chỗ đánh dấu như trên hình để vào cài đặt nâng cao (đối với phiên bản 1.0.5 trở về trước)

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B04.jpg)

Từ phiên bản 1.0.6, di chuyển xuống phía dưới chọn `Miscellaneous Settings`

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B04-1.jpg)

Bước 5: Chọn `Based on Filter` tại mục `Running Mode`

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B05.jpg)

Bước 6: Chọn `Always On` tại mục `VPN`

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B06.jpg)

# Đồng bộ

Bước 7: Trở về cài đặt cấu hình, tại mục `Filter` chọn `Link`

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B07.jpg)

Nhấn `SYNC` để đồng bộ `Filter` về máy

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B07-1.jpg)

Bước 8: Trở về cài đặt cấu hình, tại mục `Rewrite` chọn `Link`

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B08.jpg)

Nhấn `SYNC` để đồng bộ `Rewrite` về máy

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B08-1.jpg)

Trở về cài đặt cấu hình, kích hoạt tính năng `Rewrite` như hình

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B08-2.jpg)

# Bật tính năng HTTPS

> Tính năng `https` sẽ gây hao lượng pin đáng kể của thiết bị, nếu bạn muốn chặn thêm ở Youtube thì cân nhắc kích hoạt chế độ này.

Bước 9: Chọn `Install CA` tại mục `MitM` để cài đặt chứng chỉ CA

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B09.jpg)

Bước 10: Nhấn `Allow` (`Cho phép`) để bắt đầu cài đặt chứng chỉ

* Lưu ý: Kể từ iOS 12.2, bạn phải vào `Setting` của iOS mới tiếp tục cài đặt chứng chỉ do iOS không tự động chuyển qua như iOS trước

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B10.jpg)

Cài đặt và nhập passcode theo yêu cầu của iOS, nhấn `Done` (`Xong`) để hoàn tất

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B10-1.jpg)

Sau khi trở lại ứng dụng, kích hoạt tính năng `MitM` như hình

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B10-2.jpg)

Tiến hành tin cậy chứng chỉ để sử dụng tính năng `HTTPS`. Vào `Setting > General > About > Certificate Trust Settings` (`Cài đặt > Cài đặt chung > Thông tin > Certificate Trust Settings`)

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B13-2.jpg)

# Kiểm tra

Bước 11: Kiểm tra lại tất cả các mục đánh dấu như hình để đảm bảo cấu hình đã cài đặt đầy đủ và chính xác

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B11.jpg)

Tại phần `Filter` và `Rewrite` có hiển thị số là đã thành công (con số có thể thay đổi khác với hình)

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B11-1.jpg)

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B11-2.jpg)

# Bật VPN

Bước 12: Bật VPN tại màn hình chính của ứng dụng

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B12.jpg)

Bước 13: Chọn `Allow` (`Cho phép`)

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B13.jpg)

Tiến hành làm theo hướng dẫn của iOS để cài đặt VPN

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B13-1.png)

Bước 14: Nếu xuất hiện dòng chữ `Running` là đã thành công

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B14.jpg)

_**Lưu ý**_, ứng dụng không tích hợp sẵn bộ lọc để chặn quảng cáo trên Safari. Do đó hãy thực hiện theo bài viết [hướng dẫn này](https://github.com/bigdargon/hostsVN/wiki/Adguard) để lướt web không bị làm phiền bởi quảng cáo.

## Cập nhật cấu hình

Thực hiện `Bước 7` và `Bước 8` để tiến hành đồng bộ nhanh `Filter` và `Rewrite`. 

Bước 15: Trong trường hợp cần thiết, cần cập nhật lại toàn bộ cấu hình, thực hiện `Bước 1` và `Bước 2`. Sau đó chọn cấu hình đã tải trước đây

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B15.jpg)

## Báo lỗi

> Trong quá trình sử dụng, trong danh sách tên miền chặn có thể dẫn đến lỗi khi sử dụng một số phần mềm khác. Theo các bước sau để bật nhật ký chặn của ứng dụng để báo lỗi tại đây https://github.com/bigdargon/hostsVN/issues

Bước 16: Tại mục `Activity` chọn `Events`

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B16.jpg)

Chụp ảnh màn hình log và gửi báo lỗi đến địa chỉ https://github.com/bigdargon/hostsVN/issues để tiến hành báo lỗi, bạn ghi càng chi tiết càng tốt để quá trình xử lý lỗi được nhanh hơn!

![](https://raw.githubusercontent.com/bigdargon/hostsVN/gh-pages/wiki/img_QuantumultX_B16-1.png)