---
description: Step by step to create Page Grid
---

# Create Page Grid

1.  Click on Grid

    <figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>
2. Grid Detail

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

*   <mark style="color:blue;">**Highlight:**</mark>&#x20;

    <figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>After enabled "Highlight"</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**Tên ("Name"):**</mark> A field to input the name of the grid.
* <mark style="color:blue;">**Trường dữ liệu ("Data field"):**</mark> A field to specify the data field associated with the grid. That data name will match with the variable name of value which return. Example if you return\
  `{` \
  `"id": "12345",` \
  `"name": "John Doe",` \
  `"email": "john.doe@example.com",` \
  `"password": "securePassword123"` \
  `}` <mark style="color:orange;">**"id"**</mark> will match with the your input name <mark style="color:orange;">**("id")**</mark>
* <mark style="color:blue;">**Điều kiện ẩn ("Hidden condition"):**</mark> A field to define conditions under which the grid or specific data fields are hidden.
*   <mark style="color:blue;">**Phân Quyền ("Permission"):**</mark> A section to set permissions for the grid, with an option to add more permissions.

    <figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>
*   <mark style="color:blue;">**Kiểu dữ liệu ("Data type"):**</mark> A dropdown menu to select the type of data displayed in the grid (e.g., text, number, date). If you select number type then below will show the Format number button. Ex: <mark style="color:green;">1000</mark> (non-format) -> <mark style="color:green;">1,000</mark> (format on).

    <figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>
*   <mark style="color:blue;">**Danh sách có sẵn (Items):**</mark> This field gives you a list as an enum list and you fill in the corresponding values ​​according to Key-Value. Example: When u show in grid the gender value of user. In your database the value is <mark style="color:orange;">**0, 1 or empty**</mark>. But you want to show <mark style="color:orange;">**Male, Female or others**</mark> instead of that.

    <figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>"Danh sách có sẵn" enabled</strong></mark></p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Non using "Danh sách có sẵn"</strong></mark> </p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Using "Danh sách có sẵn"</strong></mark> </p></figcaption></figure>
*   <mark style="color:blue;">**Database chosen list:**</mark>

    <figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>
*   <mark style="color:blue;">**Display:**</mark> A field to define how the data should be displayed in the grid (e.g., image, progressbar).

    <figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>
*   <mark style="color:blue;">**Enable filtering:**</mark> A checkbox to enable filtering options for the grid data. You can defind the type of filter.

    <figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Disable Filter</strong></mark></p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Enable Filter</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**Nút bấm thay thế ("Replacement button"):**</mark> This data field is related to some more difficult operations, see more in  [<mark style="color:yellow;">Button Operations</mark>](others.md).
