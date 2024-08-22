---
description: Step by step to create Page Grid
---

# Update Page’s Grid Definition

Step 1: On the “Sửa thông tin trang” Page, click a tab named "Grid" on the tab bar.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfyfe3ROqhGbUOYG2vt0iiuHsbfm2h_bjxmtd_Gc9h8JOyr3J2vVyFi2mDFTy6P-bMpff2uyXTtdYsJxqc5i2UCeDjwqPGGHTwW69lfS7-rvkLDCYHOvcbZoK4dzIauxugx_TtPh4BtXIzgb2M5m3poWrcf4Dqd2Ue6QoF9cx8C2JSGJCsGhdA?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Create/Update Grid of the page</p></figcaption></figure>

Step 2: Let’s fill in any definition that you want, the field’s detail is explained below.

* To create a new  field, click on the “+” button on the fields list on the left side
* To duplicate a field, click on any field under the fields list and click on the “Copy” button.
* To delete a field, click on the delete icon in any field under the fields list.

**Highlight:** If a record has data that matches the Highlight condition, the record will be colored according to the defined configuration.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd_i34Q57TRq1op0ITJisiBDVpWZk4Q2m_BevBldoCTHTyeeE2gP5Oiu1oQn4JFE7zK_ffvT1PG34uI2aMDQor5cBiGsPozpKmrIVhIa5kv33ZCSRsnuj1DsMP4tP2Us95XUF5-hzXXuNs1ToGnho1vx1jSGbAgdpIs3BGxMOmNpK8SdWnOY8M?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Highlight setting</p></figcaption></figure>

* To see more syntax: Click [here](../references/expression.md).
* Highlight Color: green, red, orange or get “Hex code” in [colorpicker.me](https://colorpicker.me/)

<mark style="color:blue;">**Tên ("Name"):**</mark> A field to input the name of the grid.

<mark style="color:blue;">**Trường dữ liệu ("Data field"):**</mark> The data field will be mapped to the data field returned by the server, and its name is like a field in a schema of the database, so try to enter the data field name carefully and exactly.

<mark style="color:blue;">**Điều kiện ẩn ("Hidden condition"):**</mark> If the condition specified in this field is met, this field will be hidden. Example:  {"this.orderNumber":{">":1\}}

* To see more syntax: Click [here](../references/expression.md).

<mark style="color:blue;">**Phân Quyền ("Permission"):**</mark> Users click on “Phân quyền” to select the available roles to limit the type of users who see the column.

<mark style="color:blue;">**Kiểu dữ liệu ("Data type"):**</mark> A dropdown menu to select the type of data displayed in the grid (e.g., text, number, date). If you select number type then below will show the “<mark style="color:orange;">Format number</mark>” button. Ex: 1000 (non-format) -> 1,000 (format on).

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeziJyxfeZhO2fUDyOcqA968in0dXAw5YIN-0RlWO5HlUktM_gkeA2qE5T260_R7b8x4ZMjlhLmthcHq-ijw8Bho5oZ7VISvBo9fEDE0mgs4oc_ZtyURJuJmrpF5dLvQ0yN6bvK2J-44XGLnK6IJO3FYD3pQ5a4kDX8LEHZKgib2siOu8n3Dw?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Select ”Kiểu dữ liệu” dropdown</p></figcaption></figure>

<mark style="color:blue;">**Danh sách có sẵn ("Items"):**</mark> This field gives you a list as an enum list and you fill in the corresponding values ​​according to Key-Value. Example: When you show the grid the gender value of the user. In your database, the value is “0”, “1”. But you want to show “Active”, “Inactive” instead, do as below.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfC1lpNzaGBKpxm0VP2h4tPZUcST2kB3xL2nDMei-ryLhsXNREQJWkCRU1dCXAYRjCqM2ctq9zKiJIPC593pFTmtcIwFSmG36fJCo5VCksxioYl0hH6oEX7EKpeo7XCj61z-rGlmMfa_xjqdbc9-oIG78lch8RFzDPVFj3zcg?key=SHneWa61M1ec4tMp41OIHQ" alt=""><figcaption><p>“Danh sách có sẵn” setting</p></figcaption></figure>

<mark style="color:blue;">**Danh sách chọn CSDL ("Database chosen list"):**</mark> Users can replace the data of the column by calling another API to show different data. For example, if the column sho

* <mark style="color:blue;">**Single select:**</mark> the column stores only number
* <mark style="color:blue;">**Array select:**</mark> the column stores an array  \[1,2,3,4,5]

<mark style="color:blue;">**Hàm xem danh sách:**</mark> API to get data and map to the column.

<mark style="color:blue;">**Điều kiện ẩn tìm kiếm:**</mark> Additional conditions for API to hide records that match the condition

<mark style="color:blue;">**Hiển thị các trường dữ liệu:**</mark> used for filters, when a popup is opened, these fields will be displayed.&#x20;

<mark style="color:blue;">**Hiển thị các trường dữ liệu:**</mark> used for filters, when a popup is opened, these fields will be displayed.&#x20;

<mark style="color:blue;">**Select:**</mark> The specified data field is displayed on the column, replacing the column's old data.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfuEvCKwdIVFXB3iILyD-EMIv5HUP824O9RpLlbWgxnxSKQC9OS_VWmcot6AFW03sutJQSpCW-5yPvww0Ua_wSUx7lQvS0BoKEX3nI9MhJPPZk8Wj_WsUm0gpZRQUZ0aClO8e6Mjwp6Z6oobg5hjIQKWzlyzJONxDHISllqxg?key=SHneWa61M1ec4tMp41OIHQ" alt=""><figcaption><p>“Danh sách chọn csdl” setting</p></figcaption></figure>

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd4iARekyKCpswT-DW2SPtjgc-tZMOLxjraiKkCM2UwQSne0QfRG-V9jCNgNtnLuR3DtL_IVa7fPW-P67UXhDb73wlr_i2h8pcjMb4IBOkap26iGJ7B_dGKgAlPTS-9CVDi-mGR7QTyJcRtsInn_srz4Q6cTlHWvuRCiUwTug?key=SHneWa61M1ec4tMp41OIHQ" alt=""><figcaption><p><strong>Select “Hiển thị” dropdown</strong></p></figcaption></figure>

* Hiển thị ("Display"): Users can choose the type of display.
* None: Normal data, almost case.
* Image: data is an image link.
* Progressbar: data is numeric, show % complete.

Cho phép lọc ("Enable filtering"): A checkbox to enable filtering options for the grid data. You can define the type of filter.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd6-1UxHUbg0PY_9gHoy4qBUwcvha38N5KNn3riywLUgIupZsP9KD_2NxStM-NQWAP-nrOtZ1ypnOiBzJwUeAKY1UYWfk1U-U-fErlN9NfaH5hw8PH4D26Iv_aaNKk-yBwXWOK88m2pDgP1avYm9CFN4w2rWE4PjdBAEY9K?key=SHneWa61M1ec4tMp41OIHQ" alt=""><figcaption><p>Not using Filterable</p></figcaption></figure>

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfIhqX1f9Gpp_XRPHiq80q--o-9C3KC4LgOqTt5tamTgf9e9hnla6qhU52mI1Sa9BV1iodN6_U0g5QEpbTEa3UX4_7ga9BFOIY-cKh_Fo_dSN6kdsJo7JkQPsq2OTD3ibO7Ah4RQyiJKN-VzGscLTyTKyNP2SKzLfJt0ugs_A?key=SHneWa61M1ec4tMp41OIHQ" alt=""><figcaption><p>Using Filterable</p></figcaption></figure>

* <mark style="color:blue;">**Nút bấm thay thế ("Replacement button"):**</mark> This data field is related to some more difficult operations, see more in  [Button Operations](../references/button-operation.md).

**Step 3:** Click “Update” button.
