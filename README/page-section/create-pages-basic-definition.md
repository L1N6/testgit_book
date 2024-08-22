# Create Page’s Basic Definition

**Step 1:** On “Danh sách trang” page, click on the “Tạo mới ” button and redirect to the “Tạo trang mới” Page.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeZ59kbHROPT973AIhZvLPv5k__c1JZEbF28Msn9_FPK7NI57fCRpsROph02b9_eU234Iz5hNf3I2oL7Q8pgmXh6HXPCS-bQ3_ouMiPW3yVT3CDeB-5i6dnFCt29EY_JYHb2C6lcZ-KQ967jSVrVggObGVZlK3qhi4WhAPzPLDKl5x6EHgsivE?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption></figcaption></figure>

\*Note: There are 4 tabs with these features below:

* [Form:](https://quanglinhtas-organization.gitbook.io/pgea-user-guide/page-section/create-page-form) This tab provides options to build a form on the page. It includes a group of fields and button definitions in that form. See more in [here](update-pages-form-definition.md).
* [Button:](https://quanglinhtas-organization.gitbook.io/pgea-user-guide/page-section/create-page-button) This tab allows users to configure attributes or actions of a button for the page or form. See more in [here](update-pages-button-definition.md).
* [API:](https://quanglinhtas-organization.gitbook.io/pgea-user-guide/page-section/create-page-api) This tab is used to define APIs for the page. See more in [here](update-pages-api-definition.md).
* [Grid:](https://quanglinhtas-organization.gitbook.io/pgea-user-guide/page-section/create-page-grid) Define the columns in the table, the data is fetched from the API access you define in the "Hàm tải dữ liệu" and mapped to the columns. See more in [here](update-pages-grid-definition.md).

**Step 2:** Fill in the basic information field.

* Tên trang(\*): Page's display name.
* Mô tả : Page's description.

Hàm tải dữ liệu: Specified API that you already created to get data when you access the page. How to create API? Reference [here](update-pages-api-definition.md).

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfXhMLMSJr51dDgKV7FlMNqJ81E2Ok4blQqWwh_YVPZv34YcQNuzm8dB5vvlQd-FJHkxHeLYqJ2TD4KB5b0WMChbi-pJuD1zOI4vcuR3UYHTlxoB6r9r2XVt6NMMv60sI8Tl3XStztkqysRmlKlx8tku15nVIK7H0lFZPa3pAmC1yT8VKdAf4Y?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption></figcaption></figure>

**Phân quyền:** Select 1 or more roles to decide who has access to the page.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXebKEeOhzI4daUFkfxEChqcIrE3CK90bd_HEh4pTDeoZ9iy7VvxFrTq_8B6S4zOLKng_mHaaga7u-H866wvIMAnLrIax2puXtQZjlQKULIwbv2-WxGmGL1e_CZ4O_Cuye_1vfA0CkQd7coPAQqUOZaNRCs8y62tCjdP1zmo7A5OraSilNzihTA?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption></figcaption></figure>

Note: if you want to create a page for public users (users who are not required to log in when accessing the site), you should select the “Public” role to allow them to access the page that is not required to log in when accessing the site.

**Step 3:** Click on the“Create” button.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfcfBLYgSOkCO-DhXC1XUqzaWVOldu4CtmqfYd9U_v-YaXUXu-iFoLLMhT0TS_BS1eTwoWt2bWMmgODTatsDvRqGpAf8vF4BrxWJsglc6zREzVs11XWBMei892TdIqCtyok--MF4ENrYgwmg4IiqVJ_8NHvdlsPbFrIGzNs_E0anZcnvSRO7g?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption></figcaption></figure>

\
**Step 4:** To access the page that you are created currently, access page “Quản lý trang” to get the page’s id => access URL: http://localhost:5000/list/?page=id\
