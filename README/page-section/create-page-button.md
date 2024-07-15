---
description: Step by step to create Page Button
---

# Create Page Button

1.  Click on Button

    <figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
2.  Button Detail

    <figure><img src="../.gitbook/assets/image (8) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Button UI fields information 1</strong></mark></p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (11) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Button UI fields information 2</strong></mark></p></figcaption></figure>

* <mark style="color:blue;">**Chế độ (**</mark><mark style="color:orange;">**"Mode"**</mark><mark style="color:blue;">**):**</mark> A field to specify the mode or state of the button.
* <mark style="color:blue;">**Tên (**</mark><mark style="color:orange;">**"Name"**</mark><mark style="color:blue;">**):**</mark> A field to input the name of the button.
*   <mark style="color:blue;">**Phân Quyền (**</mark><mark style="color:orange;">**"Permission"**</mark><mark style="color:blue;">**):**</mark> A section to set permissions for the button, with an option to add more permissions.

    <figure><img src="../.gitbook/assets/image (12) (1).png" alt=""><figcaption></figcaption></figure>
*   <mark style="color:blue;">**Màu nút ("Color"):**</mark> A field to specify the color of the button.

    <figure><img src="../.gitbook/assets/image (13) (1).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**Outline:**</mark> A checkbox to determine if the button should have an outline.
*   <mark style="color:blue;">**BIểu tượng ("Icon"):**</mark> A field to add an icon to the button. You can get icon in [FontAwsome](https://fontawesome.com/).

    <figure><img src="../.gitbook/assets/image (14) (1).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**Hiển thị trên cột ("Show on column"):**</mark> This data field is related to some more difficult operations, see more in [<mark style="color:yellow;">Button Operations</mark>](others.md).
* <mark style="color:blue;">**Dữ liệu ẩn ("Hidden condition"):**</mark> A field to define conditions under which the button is hidden. Example: <mark style="color:orange;">**{"hideExpression":\[{"this.openUrl":{"=":""\}},{"this.openUrl":{"=":null\}}]}**</mark>
*   <mark style="color:blue;">**Kích hoạt ("After click"):**</mark> A field to specify what happens after the button is clicked. Options can include calling an API, redirecting the view, showing a pop-up, etc. Each type of acting will have some related fields. Ex: When u want to call a function after clicking, you choose calling function and select the function (that function is the api of your page) .

    <figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>After select "Gọi hàm"</strong></mark></p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>After select "Chuyển hướng"</strong></mark></p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (10) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>After select "Báo cáo"</strong></mark></p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (11) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>After select "Form Popup"</strong></mark></p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>After select "List Popup"</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**Xác nhận ("Confirm"):**</mark> A checkbox to enable a confirmation step before the button's action is performed.
*   <mark style="color:blue;">**Quay lại khi submid ("Run back after submit"):**</mark> A checkbox to determine if the user should be redirected back after the form is submitted. You can choose the link after click that button.

    <figure><img src="../.gitbook/assets/image (21) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Enabled "Quay lại khi submit"</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**Nhúng dữ liệu URL ("URL embedding"):**</mark> A field to specify if URL embedding is needed.
*   <mark style="color:blue;">**Kiểu nút ("Button Type"):**</mark> A dropdown menu to select the type of button (e.g., submit, reset).

    <figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>List "Kiểu nút"</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**Show on top:**</mark> This data field is related to some more difficult operations, see more in  [<mark style="color:yellow;">Button Operations</mark>](others.md).
* <mark style="color:blue;">**Show on form only:**</mark> This data field is related to some more difficult operations, see more in  [<mark style="color:yellow;">Button Operations</mark>](others.md).
