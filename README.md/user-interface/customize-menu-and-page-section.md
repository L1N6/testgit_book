---
description: Step by step to create a new page and menu for helping management.
---

# Customize Menu and Page Section



### I. Create Menu

1. Look at  your navigation bar on the left site, click on **System management**![](<../.gitbook/assets/Screenshot 2024-06-12 202827.png>)
2.  Click on <mark style="color:green;">**NEW**</mark> button&#x20;

    <figure><img src="../.gitbook/assets/Screenshot 2024-06-12 203150.png" alt=""><figcaption></figcaption></figure>

    then the pop-up is going to show like below :arrow\_down:

    <figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>
3. Fill all the attributes:

* <mark style="color:purple;">**Menu name**</mark>**:** Name of your menu
* <mark style="color:purple;">**Parent Menu**</mark>**:** You can choose what's parent Menu of your menu \
  ![](<../.gitbook/assets/image (22).png>)
* <mark style="color:purple;">**Is Parent Menu**</mark>**:** You can choose to use this parent menu or not
* <mark style="color:purple;">**Ordinal Menu**</mark>**:** Default = 0
* <mark style="color:purple;">**Url**</mark>**:** Url to redirect you to the page that u want with path /list?page=<mark style="color:blue;">**page\_number**</mark> \
  <mark style="color:orange;">**Note**</mark>: You can create Page before creating menu then take the <mark style="color:yellow;">**page\_id**</mark> and replace with <mark style="color:blue;">page\_number</mark>&#x20;
* <mark style="color:purple;">**Icon**</mark>**:** You can go [Font-Awesome](https://fontawesome.com/) to get icon
* <mark style="color:purple;">**Permission**</mark>**:** You can define what's role can see that menu![](<../.gitbook/assets/image (23).png>)

### II. Create Pages

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

4.  Form Detail

    <figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

* <mark style="color:blue;">**Name:**</mark> A field to specify the name of the attribute.
* <mark style="color:blue;">**Data field:**</mark> A field to designate the data field associated with the attribute.
* <mark style="color:blue;">**Placeholder:**</mark> A field to enter placeholder text, which will appear inside the input field when it is empty.
* <mark style="color:blue;">**Permission:**</mark> A section to set permissions for the attribute, with an option to add more permissions.
* <mark style="color:blue;">**Required field:**</mark> A checkbox to indicate if the field is mandatory.
* <mark style="color:blue;">**Required condition:**</mark> A field to define conditions under which the field becomes mandatory.
* <mark style="color:blue;">**Disable:**</mark> A checkbox to disable the field.
* <mark style="color:blue;">**Disable condition:**</mark> A field to specify conditions under which the field is disabled.
* <mark style="color:blue;">**Data type:**</mark> A dropdown menu to select the type of data for the field (e.g., text, number).
* <mark style="color:blue;">**Ui type:**</mark> A dropdown menu to select the type of user interface for the field (e.g., textbox, dropdown).
* <mark style="color:blue;">**Hidden conditions:**</mark> A field to specify conditions under which the field is hidden.
* <mark style="color:blue;">**Default value:**</mark> A field to set a default value for the attribute.

5. Button Detail

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

* <mark style="color:blue;">**Mode:**</mark> A field to specify the mode or state of the button.
* <mark style="color:blue;">**Name:**</mark> A field to input the name of the button.
* <mark style="color:blue;">**Permission:**</mark> A section to set permissions for the button, with an option to add more permissions.
* <mark style="color:blue;">**Color:**</mark> A field to specify the color of the button.
* <mark style="color:blue;">**Outline:**</mark> A checkbox to determine if the button should have an outline.
* <mark style="color:blue;">**Icon:**</mark> A field to add an icon to the button.
* <mark style="color:blue;">**Show on column:**</mark> A checkbox to specify if the button should be displayed in a column.
* <mark style="color:blue;">**Hidden condition:**</mark> A field to define conditions under which the button is hidden.
* <mark style="color:blue;">**After click:**</mark> A field to specify what happens after the button is clicked. Options can include calling an API, redirecting the view, showing a pop-up, etc.
* <mark style="color:blue;">**Confirm:**</mark> A checkbox to enable a confirmation step before the button's action is performed.
* <mark style="color:blue;">**Run back after submit:**</mark> A checkbox to determine if the user should be redirected back after the form is submitted.
* <mark style="color:blue;">**URL embedding:**</mark> A field to specify if URL embedding is needed.
* <mark style="color:blue;">**Button Type:**</mark> A dropdown menu to select the type of button (e.g., submit, reset).
* <mark style="color:blue;">**Show on top:**</mark> A checkbox to indicate if the button should be displayed at the top of the form.
* <mark style="color:blue;">**Show on form only:**</mark> A checkbox to indicate if the button should only be displayed on the form.

6. API Detail

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

* <mark style="color:blue;">**Name:**</mark> A field to input the name of the API call.
* <mark style="color:blue;">**Type:**</mark> A dropdown menu to select the type of API call (e.g., Create, Update, Find).
* <mark style="color:blue;">**URL:**</mark> A field to enter the URL endpoint for the API call.
* <mark style="color:blue;">**Description:**</mark> A text field to provide a description of the API call.
* <mark style="color:blue;">**Http method:**</mark> A dropdown menu to select the HTTP method used for the API call (e.g., GET, POST, PUT, DELETE).
* <mark style="color:blue;">**Using captcha:**</mark> A checkbox to indicate if captcha verification is required for the API call.
* <mark style="color:blue;">**Permission:**</mark> A section to set permissions for the API call, with an option to add more permissions.
* <mark style="color:blue;">**Upload options(update data):**</mark>
* <mark style="color:blue;">**Update options(where):**</mark>
* <mark style="color:blue;">**Upload data:**</mark>
* <mark style="color:blue;">**Retrict data upload(retrict field):**</mark> A field to define restrictions on which data fields can be uploaded.
* <mark style="color:blue;">**Response Data:**</mark> A field to specify how the response data from the API call should be handled.
* <mark style="color:blue;">**Query:**</mark> A field to define any query parameters required for the API call.
* <mark style="color:blue;">**Bool Expression:**</mark>
* <mark style="color:blue;">**Export Report:**</mark>

7. Grid Detail

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

* <mark style="color:blue;">**Name:**</mark> A field to input the name of the grid.
* <mark style="color:blue;">**Data field:**</mark> A field to specify the data field associated with the grid.
* <mark style="color:blue;">**Hidden condition:**</mark> A field to define conditions under which the grid or specific data fields are hidden.
* <mark style="color:blue;">**Permission:**</mark> A section to set permissions for the grid, with an option to add more permissions.
* <mark style="color:blue;">**Data type:**</mark> A dropdown menu to select the type of data displayed in the grid (e.g., text, number, date).
* <mark style="color:blue;">**List available:**</mark>
* <mark style="color:blue;">**Database chosen list:**</mark>
* <mark style="color:blue;">**Display:**</mark> A field to define how the data should be displayed in the grid (e.g., image, progressbar).
* <mark style="color:blue;">**Enable filtering:**</mark> A checkbox to enable filtering options for the grid data.
* <mark style="color:blue;">**Replacement button:**</mark>

8. Others

* You can copy Page, Form, Button and Grid by clicking on <img src="../.gitbook/assets/image (16).png" alt="" data-size="line">
*
