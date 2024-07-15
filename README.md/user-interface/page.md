---
description: Step by step to create a new page for helping management.
---

# Customize Page Section

### Create Pages

1. Look at  your navigation bar on the left site, click on **System management**![](<../.gitbook/assets/Screenshot 2024-06-12 213505.png>)
2. Click on <mark style="color:green;">**NEW**</mark> button&#x20;
3.  Create Page Detail

    <figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

* <mark style="color:blue;">**Name:**</mark> Page's name.
* <mark style="color:blue;">**Description:**</mark> Page's description.
*   <mark style="color:blue;">**Load data function:**</mark> Contains APIs you create to show data when you click on the page.(Displayed when u completed create api).&#x20;

    <figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**Language:**</mark> You can choose the language of page.
* <mark style="color:blue;">**Permission:**</mark> You can define who can use that page.

&#x20; And 4 tabs with 4 feature:

* <mark style="color:blue;">**Form:**</mark> This tab provides options to manage forms within the page. It includes a button labeled attributes  to add properties to the form.
* <mark style="color:blue;">**Button:**</mark> This tab allows users to configure buttons for the page.
* <mark style="color:blue;">**API:**</mark> This tab is used to set up API integrations for the page.
* <mark style="color:blue;">**Grid:**</mark> This tab enables users to configure grid layouts.

Those tabs

4.  Form Detail

    <figure><img src="../../README/.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption><p>Page - Form</p></figcaption></figure>

* <mark style="color:blue;">**Name (string):**</mark> A field to specify the name of the attribute. Example: Account
*   <mark style="color:blue;">**Data field:**</mark> A field to designate the variable will contains data of that form name. Example Data Field had value = account, when u fill the form and send the request u will send <mark style="color:orange;">{"account":"value"}</mark> with json format.

    <figure><img src="../../README/.gitbook/assets/Screenshot 2024-07-02 185554.png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Sample</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**Placeholder:**</mark> A field to enter placeholder text, which will appear inside the input field when it is empty.
*   <mark style="color:blue;">**Permission:**</mark> A section to set permissions for the attribute, with an option to add more permissions.

    <figure><img src="../../README/.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption><p> <mark style="color:yellow;"><strong>After Clicking "+" button</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**Required field:**</mark> A checkbox to indicate if the field is mandatory. It mean that must be fill, not empty after sending it.
* <mark style="color:blue;">**Required Expression:**</mark> A field to define conditions under which the field becomes mandatory.
* <mark style="color:blue;">**Disable:**</mark> A checkbox to disable the field.
* <mark style="color:blue;">**Disable condition:**</mark> A field to specify conditions under which the field is disabled.
*   <mark style="color:blue;">**Data type:**</mark> A dropdown menu to select the type of data for the field (e.g., text, number).

    <figure><img src="../../README/.gitbook/assets/image (3) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Sample</strong></mark></p></figcaption></figure>
*   <mark style="color:blue;">**Ui type:**</mark> A dropdown menu to select the type of user interface for the field (e.g., textbox, dropdown).

    <figure><img src="../../README/.gitbook/assets/image (4) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Sample</strong></mark></p></figcaption></figure>
*   <mark style="color:blue;">**Array input:**</mark> If you want to input an array and send it to backend. Click that and put your button name below.

    <figure><img src="../../README/.gitbook/assets/image (6) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Sample</strong></mark></p></figcaption></figure>

    <figure><img src="../../README/.gitbook/assets/image (7) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>After Using</strong></mark></p></figcaption></figure>


* <mark style="color:blue;">**REGEX (REGEX FLAG):**</mark> Regex is a pattern (or filter) that describes a set of strings that matches the pattern. Example: <mark style="color:orange;">**"^a-zA-Z0-9+\[a-zA-Z0-9]$"**</mark>
* <mark style="color:blue;">**Error On Regex Fail:**</mark> The message you want to show when fail checking regex above.
* <mark style="color:blue;">**Hidden conditions:**</mark> A field to specify conditions under which the field is hidden.
* <mark style="color:blue;">**Default value:**</mark> A field to set a default value if you input nothing then sending to backend. It could be <mark style="color:orange;">**"0"**</mark> when your data type is number or <mark style="color:orange;">empty</mark> with string type.

5.  Button Detail

    <figure><img src="../../README/.gitbook/assets/image (8) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Picture - 1</strong></mark></p></figcaption></figure>

    <figure><img src="../../README/.gitbook/assets/image (11) (1) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Picture - 2</strong></mark></p></figcaption></figure>

* <mark style="color:blue;">**Mode:**</mark> A field to specify the mode or state of the button.
* <mark style="color:blue;">**Name:**</mark> A field to input the name of the button.
*   <mark style="color:blue;">**Permission:**</mark> A section to set permissions for the button, with an option to add more permissions.

    <figure><img src="../../README/.gitbook/assets/image (12) (1).png" alt=""><figcaption></figcaption></figure>
*   <mark style="color:blue;">**Color:**</mark> A field to specify the color of the button.

    <figure><img src="../../README/.gitbook/assets/image (13) (1).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**Outline:**</mark> A checkbox to determine if the button should have an outline.
*   <mark style="color:blue;">**Icon:**</mark> A field to add an icon to the button. You can get icon in [FontAwsome](https://fontawesome.com/).

    <figure><img src="../../README/.gitbook/assets/image (14) (1).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**Show on column:**</mark> A checkbox to specify if the button should be displayed in a column.
* <mark style="color:blue;">**Hidden condition:**</mark> A field to define conditions under which the button is hidden.
*   <mark style="color:blue;">**After click:**</mark> A field to specify what happens after the button is clicked. Options can include calling an API, redirecting the view, showing a pop-up, etc. Each type of acting will have some related fields. Ex: When u want to call a function after clicking, you choose calling function and select the function (that function is the api of your page) .

    <figure><img src="../../README/.gitbook/assets/image (15) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Sample 1</strong></mark></p></figcaption></figure>

    <figure><img src="../../README/.gitbook/assets/image (16) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Sample 2</strong></mark></p></figcaption></figure>

    <figure><img src="../../README/.gitbook/assets/image (20) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Sample 3</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**Embeded Value:**</mark>
* <mark style="color:blue;">**Confirm:**</mark> A checkbox to enable a confirmation step before the button's action is performed.
*   <mark style="color:blue;">**Run back after submit:**</mark> A checkbox to determine if the user should be redirected back after the form is submitted. You can choose the link after click that button.

    <figure><img src="../../README/.gitbook/assets/image (21) (1).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Sample</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**URL embedding:**</mark> A field to specify if URL embedding is needed.
* <mark style="color:blue;">**Button Type:**</mark> A dropdown menu to select the type of button (e.g., submit, reset).
* <mark style="color:blue;">**Show on top:**</mark> A checkbox to indicate if the button should be displayed at the top of the form.
* <mark style="color:blue;">**Show on form only:**</mark> A checkbox to indicate if the button should only be displayed on the form.

6.  API Detail

    <figure><img src="../../README/.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

* <mark style="color:blue;">**Name:**</mark> A field to input the name of the API call.
*   <mark style="color:blue;">**Type:**</mark> A dropdown menu to select the type of API call (e.g., Create, Update, Find). That type to identify the blueprint functions.

    <figure><img src="../../README/.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../README/.gitbook/assets/image (24).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Customize Blueprint Functions</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**URL:**</mark> A field to enter the URL endpoint for the API call.
* <mark style="color:blue;">**Description:**</mark> A text field to provide a description of the API call.
*   <mark style="color:blue;">**Http method:**</mark> A dropdown menu to select the HTTP method used for the API call (e.g., GET, POST, PUT, DELETE).

    <figure><img src="../../README/.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**Using captcha:**</mark> A checkbox to indicate if captcha verification is required for the API call. When u
*   <mark style="color:blue;">**Permission:**</mark> A section to set permissions for the API call, with an option to add more permissions.

    <figure><img src="../../README/.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**Upload options(update data):**</mark>
* <mark style="color:blue;">**Update options(where):**</mark>
* <mark style="color:blue;">**Upload data:**</mark>
*   <mark style="color:blue;">**Retrict data upload(retrict field):**</mark> A field to define restrictions on which data fields can be uploaded. Your backend return a lot of fields but some fields you  don't want to show because of authentication. Example: You response a Json Object:\
    `{` \
    `"id": "12345",` \
    `"name": "John Doe",` \
    `"email": "john.doe@example.com",` \
    `"password": "securePassword123"` \
    `}` And you don't want to show the password you can input the passwod to ignore it.\


    <figure><img src="../../README/.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>
*   <mark style="color:blue;">**Response Data:**</mark> You can define the fields you want returned.

    <figure><img src="../../README/.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**Query:**</mark> A field to define any query parameters required for the API call.
* <mark style="color:blue;">**Bool Expression:**</mark>
* <mark style="color:blue;">**Export Report:**</mark>

7.  Grid Detail

    <figure><img src="../../README/.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

* <mark style="color:blue;">**Name:**</mark> A field to input the name of the grid.
* <mark style="color:blue;">**Data field:**</mark> A field to specify the data field associated with the grid. That data name will match with the variable name of value which return. Example if you return\
  `{` \
  `"id": "12345",` \
  `"name": "John Doe",` \
  `"email": "john.doe@example.com",` \
  `"password": "securePassword123"` \
  `}` <mark style="color:orange;">"id"</mark> will match with the your input name(id)
* <mark style="color:blue;">**Hidden condition:**</mark> A field to define conditions under which the grid or specific data fields are hidden.
*   <mark style="color:blue;">**Permission:**</mark> A section to set permissions for the grid, with an option to add more permissions.

    <figure><img src="../../README/.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>
*   <mark style="color:blue;">**Data type:**</mark> A dropdown menu to select the type of data displayed in the grid (e.g., text, number, date). If you select number type then below will show the Format number button. Ex: <mark style="color:green;">1000</mark> (non-format) -> <mark style="color:green;">1,000</mark> (format on).

    <figure><img src="../../README/.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>
* <mark style="color:blue;">**List available:**</mark>
* <mark style="color:blue;">**Database chosen list:**</mark>
* <mark style="color:blue;">**Display:**</mark> A field to define how the data should be displayed in the grid (e.g., image, progressbar).
*   <mark style="color:blue;">**Enable filtering:**</mark> A checkbox to enable filtering options for the grid data. You can defind the type of filter.

    <figure><img src="../../README/.gitbook/assets/image (32).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Non Filter</strong></mark></p></figcaption></figure>

    <figure><img src="../../README/.gitbook/assets/image (33).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Filter</strong></mark></p></figcaption></figure>

    <figure><img src="../../README/.gitbook/assets/image (34).png" alt=""><figcaption><p><mark style="color:yellow;"><strong>Filter Sample</strong></mark></p></figcaption></figure>
* <mark style="color:blue;">**Replacement button:**</mark>

8. Others

* You can copy Page, Form, Button and Grid by clicking on <img src="../.gitbook/assets/image (16).png" alt="" data-size="line">

