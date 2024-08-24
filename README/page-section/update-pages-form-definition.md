---
description: Step by step to create Page Form
---

# Update Page’s Form Definition

Step 1: Still “Danh sách trang” Page, click on the “Sửa” button on any record that you want to update.

Step 2: Click a tab named "Form" on the tab bar.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfYKz8iuMSliYahzueqRvzQCrZzz94BtdD_RLw6kwmwRPZZUfe1ImrXSZfOtNbZZaTso-heJuzhjivJioiQhG-giiw_HZZajLSeBMZFGaGC8mdheE8HlLnwiRpasJWW-7ID7K4D8q-GaJqY6GNpvRXtkRyv40cFeI5vonkmunLJixWGKoGrHA?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Create/update form for the page</p></figcaption></figure>

**Step 3:** Let’s fill in any definition that you want, the field’s detail is explained below.

* To create a new  field, click on the “+” button on the fields list on the left side
* To duplicate a field, click on any field under the fields list and click on the “Copy” button.
* To delete a field, click on the **delete icon** in any field under the fields list.

\


<mark style="color:blue;">**Tên ("Name"):**</mark> A field to specify the name of the attribute. Example: account

<mark style="color:blue;">**Trường dữ liệu ("Data field"):**</mark> The data field will be mapped to the data field returned by the server, and its name is like a field in a schema of the database, so try to enter the data field name exactly.

<mark style="color:blue;">**Placeholder:**</mark> A field to enter placeholder text, which will appear inside the input field when it is empty.

<mark style="color:blue;">**Phân quyền ("Permission"):**</mark> Users click on “Phân quyền” to select the available roles to limit the type of user access to the page’s form.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdWcDzZwSBRRMliYo4q5or9cYI7bB1cD2k8ENHKEKqK6EAeeAX7rN8kGakdBaXu2p_4GuHKnUdNZdND-rwrpzX8uN6PE4kSKJspHV1MmTiYxW97cTwL4owzhCTBj7reYZurfDZfBCV5nCzKk6GjSw10PmcXCUrrtuY5AMQ4o7_yMLlqSGGJpQ?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Select “Phân quyền ” popup</p></figcaption></figure>

<mark style="color:blue;">**Trường bắt buộc ("Required field"):**</mark> If set to true, the data field requires the user to fill in data before submitting the form.

<mark style="color:blue;">**Điều kiện bắt buộc ("Required Expression"):**</mark> If the condition defined in this field is met, this field will prompt the user to fill in data.&#x20;

* Example: <mark style="color:orange;">**{"this.orderNumber":{"=":1\}}**</mark>
* To see more syntax: Click [here](../references/expression.md).

<mark style="color:blue;">**Vô hiệu hoá ("Disable"):**</mark> Cannot fill data if setting is true

<mark style="color:blue;">**Điều kện vô hiệu hoá ("Disable condition"):**</mark> If the condition defined in this field is met, this field will be inactivated.&#x20;

* Example:  <mark style="color:orange;">**{"this.orderNumber":{"!=":1\}}**</mark>
* To see more syntax: Click [here](../references/expression.md).

<mark style="color:blue;">**Kiểu dữ liệu("Data type"):**</mark> A dropdown menu to select the type of data for the field (e.g., text, number, boolean, etc.).

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfXviZGPyk1bM_jwQ1-YXRHcL_fxIh5AwTn35TBjzNeZJW2iogjZS7IguAmWJg2IzU3FJNPSaZaf24VpBT74xeREsAwE5mGlzHBUYrJaKChiebuLP4vxL45NvaTCmpcKRZb3bSIVELBb8svwXUNWNSmzwApjk0hyB0QI6tdoNlSCMyiOsjZ_w4?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>“Kiểu dữ liệu” dropdown</p></figcaption></figure>

<mark style="color:blue;">**Kiểu giao diện ("Widget"):**</mark> Users can select the type of input UI. Ex: text, Enum, textArea, enumButton, Captcha, etc. Click [here](../references/forms-widget-demo/).

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXf5y8Y1z7Ssm2TBcDBxmI8xQf7eHEaFNd9MFCIwisX5-9f7VbgmZ0dWNVt7DIl7bTasvtU_5PDZJ5gprLKOYjSLPf2h6_jVZJJeNy3LGN0oJJMjThnqmPvykV8MGu8MtL7CE7DmMvW5jEQuO731Jj0qWL_eSAO8s3HNc2tA_8oz1Heoqiob2WM?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Select “Kiểu giao diện” dropdown</p></figcaption></figure>

<mark style="color:blue;">**Array input:**</mark> If you want to input and send to the server an array, see the following guide.

Thiếu ảnh

<mark style="color:blue;">**REGEX ("REGEX FLAG"):**</mark> Regex is a pattern (or filter) that describes a set of strings that matches the pattern. Example: <mark style="color:orange;">**"^a-zA-Z0-9+\[a-zA-Z0-9]$"**</mark>

<mark style="color:blue;">**Lỗi Regex Test Fail ("Error On Regex Fail"):**</mark> The message you want to show when you enter the wrong format of Regex.

<mark style="color:blue;">**Điều Kiện Ẩn ("Hidden conditions"):**</mark> If the condition specified in this field is met, this field will be hidden.&#x20;

* Example:  <mark style="color:orange;">**{"this.orderNumber":{">":1\}}**</mark>
* To see more syntax: Click [here](../references/expression.md).

<mark style="color:blue;">**Mặc Định ("Default value"):**</mark> A field to set a default value if you input nothing and then sending to the backend. It could be "0" when your data type is number or empty with string type. You need to choose the "Kiểu dữ liệu" and input the match value with "Kiểu dữ liệu".

**Step 3:** Click “Lưu thông tin” button.

**Step 4:** Access that page’s form using that path URL format: \
<mark style="color:orange;">**form/?page=**</mark><mark style="color:blue;">**idOfPage**</mark><mark style="color:orange;">**\&mode=**</mark><mark style="color:blue;">**thatModeInButtonTab**</mark>
