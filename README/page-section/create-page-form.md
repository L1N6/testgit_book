---
description: Step by step to create Page Form
---

# Create Page Form

1.  Click "Form" on list Page tabs

    <div align="left">

    <figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

    </div>
2. Form Detail

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;">Page - Form</mark></p></figcaption></figure>

* <mark style="color:blue;">**Tên (**</mark><mark style="color:orange;">**"Name"**</mark><mark style="color:blue;">**):**</mark> A field to specify the name of the attribute. Example: Account
* <mark style="color:blue;">**Trường dữ liệu (**</mark><mark style="color:orange;">**"Data field"**</mark><mark style="color:blue;">**):**</mark> A field to designate the variable will contains data of that form name. Example Data Field had value = account, when u fill the form and send the request u will send <mark style="color:orange;">{"account":"value"}</mark> with json format.
* <mark style="color:blue;">**Placeholder:**</mark> A field to enter placeholder text, which will appear inside the input field when it is empty.
*   <mark style="color:blue;">**Phân quyền (**</mark><mark style="color:orange;">**"Permission"**</mark><mark style="color:blue;">**):**</mark> A section to set permissions for the attribute, with an option to add more permissions.

    <figure><img src="../.gitbook/assets/image (2) (1) (1) (1).png" alt=""><figcaption><p> <mark style="color:yellow;"><strong>After Clicking "+" button</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**Trường bắt buộc (**</mark><mark style="color:orange;">**"Required field"**</mark><mark style="color:blue;">**):**</mark> A checkbox to indicate if the field is mandatory. It mean that must be fill, not empty after sending it.
* <mark style="color:blue;">**Điều kiện bắt buộc (**</mark><mark style="color:orange;">**"Required Expression"**</mark><mark style="color:blue;">**):**</mark> A field to define conditions under which the field becomes mandatory.
* <mark style="color:blue;">**Vô hiệu hoá (**</mark><mark style="color:orange;">**"Disable"**</mark><mark style="color:blue;">**):**</mark> A checkbox to disable the field.
* <mark style="color:blue;">**Điều kện vô hiệu hoá (**</mark><mark style="color:orange;">**"Disable condition"**</mark><mark style="color:blue;">**):**</mark> A field to specify conditions under which the field is disabled.
*   <mark style="color:blue;">**Kiểu dữ liệu(**</mark><mark style="color:orange;">**"Data type"**</mark><mark style="color:blue;">**):**</mark> A dropdown menu to select the type of data for the field (e.g., text, number).

    <figure><img src="../.gitbook/assets/image (3) (1) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Data</strong></mark></p></figcaption></figure>
*   <mark style="color:blue;">**Kiểu giao diện (**</mark><mark style="color:orange;">**"UI type"**</mark><mark style="color:blue;">**):**</mark> A dropdown menu to select the type of user interface for the field (e.g., textbox, dropdown).

    <figure><img src="../.gitbook/assets/image (4) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>UI Type</strong></mark></p></figcaption></figure>
*   <mark style="color:blue;">**Array input:**</mark> If you want to input an array and send it to backend. Click that and put your button name below.



    <figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Before Enabled</strong></mark></p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (6) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Enabled</strong></mark></p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (40).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>After Enabled</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**REGEX (**</mark><mark style="color:orange;">**"REGEX FLAG"**</mark><mark style="color:blue;">**):**</mark> Regex is a pattern (or filter) that describes a set of strings that matches the pattern. Example: <mark style="color:orange;">**"^a-zA-Z0-9+\[a-zA-Z0-9]$"**</mark>
* <mark style="color:blue;">**Lỗi Regex Test Fail (**</mark><mark style="color:orange;">**"Error On Regex Fail"**</mark><mark style="color:blue;">**):**</mark> The message you want to show when fail checking regex above.
* <mark style="color:blue;">**Điều Kiện Ẩn (**</mark><mark style="color:orange;">**"Hidden conditions"**</mark><mark style="color:blue;">**):**</mark> A field to specify conditions under which the field is hidden.
* <mark style="color:blue;">**Mặc Định (**</mark><mark style="color:orange;">**"Default value"**</mark><mark style="color:blue;">**):**</mark> A field to set a default value if you input nothing then sending to backend. It could be <mark style="color:orange;">**"0"**</mark> when your data type is number or <mark style="color:orange;">empty</mark> with string type. You need to choose the <mark style="color:orange;">"Kiểu dữ liệu"</mark> and input the match value with <mark style="color:orange;">"Kiểu dữ liệu"</mark>.
