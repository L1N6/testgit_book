---
description: Step by step to create Page Api
---

# Create Page Api

1.  Click on Api

    <figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>
2. API Detail

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

* <mark style="color:blue;">**Tên ("Name"):**</mark> A field to input the name of the API call.
*   <mark style="color:blue;">**Kiểu ("Type"):**</mark> A dropdown menu to select the type of API call (e.g., Create, Update, Find). That type to identify the blueprint functions.

    <figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Customize Blueprint Functions</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**URL:**</mark> A field to enter the URL endpoint for the API call.
* <mark style="color:blue;">**Mô tả api ("Description"):**</mark> A text field to provide a description of the API call.
*   <mark style="color:blue;">**Phương thức http ("Http Method"):**</mark> A dropdown menu to select the HTTP method used for the API call (e.g., GET, POST, PUT, DELETE).

    <figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**Đi qua capcha ("Using captcha"):**</mark> A checkbox to indicate if captcha verification is required for the API call. Prevent bot purpose.
*   <mark style="color:blue;">**Phân quyền ("Permission"):**</mark> A section to set permissions for the API call, with an option to add more permissions.

    <figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>
*   <mark style="color:blue;">**Tuỳ chọn gửi lên \[Upload options(update data)]:**</mark> This fields only use for <mark style="color:orange;">**POST**</mark> method. That provide Key-Value for helping to send more variable of Json. Example: You want to add some variable to Json before sending to Back-End. If your key-value is <mark style="color:orange;">**"name"**</mark>-<mark style="color:orange;">**"newValue"**</mark> it is similar to <mark style="color:orange;">**{"name":"newValue"}**</mark>**.**

    <figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption><p><mark style="color:yellow;">Explain feature</mark></p></figcaption></figure>
*   <mark style="color:blue;">**Tuỳ chọn cập nhật ("Update options(where)"):**</mark> This fields provide Key-Value for helping to add more where conditions on path <mark style="color:orange;">**InputQuery**</mark> with syntax like <mark style="color:orange;">**"criterias":\[{"key":"id","value":"--id"}]**</mark>

    <figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p><mark style="color:yellow;">Explain feature</mark></p></figcaption></figure>
* <mark style="color:blue;">**Dữ liệu gửi lên ("Request Fields"):**</mark> You can input the fields you want sending to Api.&#x20;
* <mark style="color:blue;">**Dữ liệu Hạn chế gửi lên \["Retrict data upload(retrict field)"]:**</mark> A field to define restrictions on which data fields can be uploaded. Your backend return a lot of fields but some fields you  don't want to show because of authentication. Example: You response a Json Object:\
  `{` \
  `"id": "12345",` \
  `"name": "John Doe",` \
  `"email": "john.doe@example.com",` \
  `"password": "securePassword123"` \
  `}`&#x20;

And you don't want to show the password you can input the passwod to ignore it.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

*   <mark style="color:blue;">**Dữ liệu trả về ("Response Fields"):**</mark> You can define the fields you want returned.

    <figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**Query:**</mark> A field to define any query parameters required for the API call.
* <mark style="color:blue;">**Bool Expression:**</mark>
* <mark style="color:blue;">**Export Report:**</mark>

<mark style="color:purple;">**Finish:**</mark> If you completed to create an Api. The new api will show on <mark style="color:orange;">**"Hàm tải dữ liệu"**</mark>.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption><p>After completed creating new</p></figcaption></figure>
