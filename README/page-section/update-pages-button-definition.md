---
description: Step by step to create Page Button
---

# Update Page’s Button Definition

**Step 1:** On the “Sửa thông tin trang” Page, click a tab named "Button" on the tab bar.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcw7plsZGdxWU5DUWXc1u9i2f0miR4RwfvcZHuBgNVgu68_tW7JNgGFMy5Woom1hLstM_Ud08c6cuUHbDzjphOizAnpEm4PYfNNzZgI9cyxENRJgyx_2mS7ra7lErtaQzPRLf8SfKS0C1nUUtOHmg4JJCcIoS_7sjVCBrYpwhl0c66K-D47R7M?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Create/update button of the page</p></figcaption></figure>

**Step 2:** Let’s fill in any definition that you want, the field’s detail is explained below.

<mark style="color:blue;">**Chế độ ("Mode"):**</mark> Name anything you want, if this button is on a form, it will appear if the embedded form's mode attribute matches the button's mode.

If you had 2 button with the same Mode value. Ex: Forgot and Close with “forgot” Mode.

* To delete a field, click on the delete icon in any field under the fields list.
* To duplicate a field, click on any field under the fields list and click on the “Copy” button.
* To create a new  field, click on the “+” button on the fields list on the left side.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcd_rcNQ__SP_QadKXpI-FSI_5-rK9hfOWNPeDIbwtXmDf6eeQ98msTg857I_kKd5uxfPEapL4K7TApFR-nKCToAI7dQUAjHp24EbKU8W1a1S5oQ40E0bHmxln64w7U04e8IjQ3QNSsh7bRym4Su48s0BMWLVTRLWKPpc-zh18pE79qRG-DVPw?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Forgot button</p></figcaption></figure>

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXci9AMx65MWGwCtZz2mBVpQmdm8a5kWZ1V9M8BgDu3AYDXjzDbBGmxrYuEfv2eM4PL-_seGQNHN7kOq6zmXkm8tYc3juPKNp46xj9zrYDs6_Y82vYAlgl6KiHxBAvesKVxZneBOsvWPfvvrO2Vr65VLP5G7XQvpxvrqu_nwbTvefxFiTehQXEY?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Close button</p></figcaption></figure>

You run the path with: <mark style="color:blue;">**/form/?page=23\&mode=forgot**</mark> you will see 2 buttons in your page’s form.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcVe3Ky4yhmZgILAAlALYAxnTkuq9jbvoDyFD5g7RHiyLQsw-29TrTSXqdQRzXYxpQt0tAl-yVdlcRW1hzdMzkd6X5uh3Oe4ygQBifn_GT9N-Sf0KzcOqOJByOOpQXhskKYYl4NSTbcgLb5OKW-1ZQXpKM-i4dzi9QWd1rTXNGFQXgZ70OAbQ?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Final Result</p></figcaption></figure>

<mark style="color:blue;">**Tên ("Name"):**</mark> A field to input the name of the button.

<mark style="color:blue;">**Phân Quyền ("Permission"):**</mark> Users click on “Phân quyền” to select the available roles to limit the type of user to use this button.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfCKOL5uGkzRLFD6BFv31hsBOIHPO5ZJj6zTB7NWzUb5YvyYRvFJtDoZ-XTYzCTEXRqNCKf73IcRFKbeKk2smOcCTG_F-A-GjD-cP-ILlAhaijcJrq8Jj6JMU10uYlYkMZvn44EsfE7jhOnditIXRW-Tby7OTtYXaLKunTUWJsE-6z3bb-WA5c?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Create menu form</p></figcaption></figure>

<mark style="color:blue;">**Màu nút ("Color"):**</mark> A field to specify the color of the button.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcyj7OsDvVWXBwwbuOLPqSr8GfjCYwlvWwBhBkq_8DQY36NqpE-AU_TdV13hgmnAgJuzgZsJrKC7kIVqT_vgn_esStZwtH-Wl8wQ1vkEUe2l2MfBv3O_eW-y6XOHXX8stIdb52jfuCysi73e75eXj_UydEldsgf29OfllYy9jY2i3u4Q-kZWFo?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Select “màu nút” dropdown</p></figcaption></figure>

<mark style="color:blue;">**Outline:**</mark> A checkbox to determine if the button should have an outline.

<mark style="color:blue;">**Biểu tượng ("Icon"):**</mark> A field to add an icon to the button. You can get an icon in[ ](https://fontawesome.com/)[Tabler.io](https://tabler.io/icons), and fill in the class of the icon.&#x20;

* Example: <mark style="color:orange;">**tabler:trash**</mark>

<mark style="color:blue;">**Hiển thị trên cột ("Show on column"):**</mark> a field’s name, the position where you want to place the button on any field in the grid if that field has the “Nút bấm thay thế" setting set to true. This data field is related to some more difficult operations, see more in  [Button Operations](../references/button-operation.md).

<mark style="color:blue;">**Điều kiện ẩn ("Hidden condition"):**</mark> If the condition specified in this button is met, this button will be hidden.&#x20;

* Example:  <mark style="color:orange;">**{"this.orderNumber":{">":1\}}**</mark>
* To see more syntax: Click [here](../references/expression.md).

<mark style="color:blue;">**Kích hoạt ("Activate"):**</mark> Action of a button: call function, redirect to another page or open form popup, etc.

* To see detailed: Cick [here](../references/activate-button.md).

<mark style="color:blue;">**Xác nhận ("Confirm"):**</mark> Fill in the message you want to display. or example, "Bạn có muốn xóa trang này không?", if you click "OK", the button will be activated.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcvk99l2nDdtLv6YRE0f6WF507BvUavtt7Y04pHqAWUxQxpap2tN4vQLNcrDpeHbkfPMgHsKE0w6UPWOdmeihIBVfxe9ByKOCjG2wQ59zD5xvHt6M0mI83srzil0TOI3jQ7dcSGXSR_RI-XucrP9YOJyilj_-3Vnw0_lzm42DuTieKVdYsdww0?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Confirm popup</p></figcaption></figure>

<mark style="color:blue;">**Quay lại khi submit ("Run back after submit"):**</mark> Users can enable go back after submitting or not. Besides, users can select the HREF to go back.&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfyCN54tMuwVdjSBu_nsw_4LW-73jJUCA-7uZUPJNqeJBciEr_rm1C26zLfGl2ObaALmj2nzLVw5a8MGy55tVrnwIitWNR6ztDjzJkWtA-wvHoj8hzQ9Nh63-mXtZslyAV-2VeWFsx4BCNerVNV-1gmuyUxjK-JPvmwVSDxUVPhOjsDlqS40MI?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>URL run back after submit</p></figcaption></figure>

<mark style="color:blue;">**Nhúng dữ liệu URL ("URL embedding"):**</mark> If it is a redirect button, the URL will have embedded data attached.

<mark style="color:blue;">**Kiểu nút ("Button Type"):**</mark> Users can select the type of button. Ex: submit, switch, button, etc.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdBnexTiBnnKxe4VkGtobgUPSGoUdvLS5T4AQ2Ic9bV7VqsbQ8mY7O37kx1LJCyO2BhXvPChvNTxSc_QcuxZB5pZY7k1BXS9nFnwjuZO5ZKZou6O-8QndZoRKO7raxrBGpf4FBAMH84jzg_XrpbPjSJfhueY7ny7BqLsWNyAQJvEbDpBzQVtJM?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Drop down for type field</p></figcaption></figure>

<mark style="color:blue;">**Show on form only:**</mark> Show button only in form, not for the grid. This data field is related to some more difficult operations, see more in  [Button Operations](../references/button-operation.md).

<mark style="color:blue;">**Show on top:**</mark> Show on the top of the form. This data field is related to some more difficult operations, see more in  [Button Operations](../references/button-operation.md).

\
