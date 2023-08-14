# Microsoft365Labs

**Bài LAB 01: Safe Links Policy**

Truy cập **Microsoft 365 Defender** portal (https://security.microsoft.com/), chọn **Policies & Rules** ở phần **Email & collaboration** > **Threat policies** > **Safe Links**

Nhấn nút dấu + để tạo mới policy, đặt tên vào ô _Name your policy_ > Next

Ở thẻ _Users and domains_, chọn danh sách các người dùng (_Users_), nhóm (_Groups_) và tên miền (_Domains_) để áp dụng policy. Trong hình ảnh minh họa, policy áp dụng cho toàn tên miền > Next. 

![image](https://github.com/hieulecyber/Microsoft365Labs/assets/102139186/e0372a32-58ba-4de6-906c-94ef61a88357)

Đánh dấu chọn thêm vào tùy chọn _Track user clicks_ và _Display the organization branding on notification and warning pages_ > Next

![image](https://github.com/hieulecyber/Microsoft365Labs/assets/102139186/fc64956b-ade3-40b0-94e4-f387a2681739)

Chọn User custom notificaton text và nhập vào thông báo vào ô _Custom nofification text_ > Next.

![image](https://github.com/hieulecyber/Microsoft365Labs/assets/102139186/e714964c-c692-4f6a-a4d4-6c24badde93d)

Chọn **Submit** để tiến hành tạo policy mới. 


![image](https://github.com/hieulecyber/Microsoft365Labs/assets/102139186/90338a65-d5b0-431b-b7e7-b0438c693434)

Trở lại **Threat Policies** > **Tenant Allow/Block Lists**, chuyển sang thẻ _URL_, chọn _Block_ và nhập địa chỉ các trang web sẽ chặn trong phần _Add URLs with wildcards (20 max)_, chọn thời gian mở khóa URL trong phần _Remove block entry after_ và nhấn nút _Add_. 

![image](https://github.com/hieulecyber/Microsoft365Labs/assets/102139186/aa814c5c-2fae-4a18-9674-687090dff4cf)



