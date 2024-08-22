---
description: Step by step to create Page Api
---

# Update Page’s API Definition

Step 1: On the “Sửa thông tin trang” Page, click a tab named "API" on the tab bar.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfcbjbZgyhKsxsPgq_JooWpiODd8sVVgf7i8cfn2OZXU1SLS8TYPlQNXCQqlusCAXkpHlfq-peGFSm6n8I7HsOPBHKywJuxcB2v7NyepfKCW-6W32tT9FX6Fh8Y49VzXdF6-oH6B3vyi2GoFvh4ZMN5P7Vz2upy_phW8oChBLqKb4IoLZsvTjk?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Create/Update the API of the page</p></figcaption></figure>

**Step 2:** Let’s fill in any definition that you want, the field’s detail is explained below.

**Step 3:** Let’s fill in any definition that you want, the field’s detail is explained below.

* To create a new  field, click on the “+” button on the fields list on the left side
* To delete a field, click on the delete icon in any field under the fields list.

<mark style="color:blue;">**Kiểu ("Type"):**</mark> A dropdown menu to select the type of API call (e.g., Create, Update, Find). That type to identify the blueprint functions.

<mark style="color:blue;">**Tên ("Name"):**</mark> A field to input the name of the API call.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfyotKZa8Kb7pwue_GVO2nPGHrhyMXx3bPcGWPoZrK9nbwb7-AwIDmO4t9cEc3LCus2WhgCM8z0Tn-CkR-pdpD1oqvG00is3JFQ_Q1Q7rKsXQDuu0mA6rK3qfv1BsSCIXJvNcWFKzoMXhXPg-Hk3VVvZwJig9S6AZoE_G-E_Wisd4LkUHJTI1g?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Type of API</p></figcaption></figure>

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXetSeVLo5nq67cHqn72C91-98xyz64ftKZ1MhNTT62HoW_15oOl2J4FLOcKVRj4p-TesDK5luMwnb-5Fl4lLV_5W_8q0kz-olXLiVmwzPfh3MwaD7P1iU470JmEpfA8KFCsF-01p8ptLk99wHLDkYToxo61LM4V572jzAlwuYzZ_rKNgwr34g?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Blueprints File</p></figcaption></figure>

<mark style="color:blue;">**URL:**</mark> A field to enter the URL endpoint for the API call. Ex: /api/user

<mark style="color:blue;">**Mô tả API ("Description"):**</mark> A text field to provide a description of the API call.

<mark style="color:blue;">**Phương thức HTTP ("HTTP Method"):**</mark> A dropdown menu to select the HTTP method used for the API call (e.g., GET, POST, PUT, DELETE).

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXemhxhw8RY6Ju6nPHZ_KU-RX1wJrc9FANYd65XZ5-T_v4r7XEUO5oVFfu1s0QVFla65m7d80nhcwo3VM7QiAVuZjcnhS-4lODLnEzKHH84sbwgLT4K83KCYBkLF7ewaIzPtMVHgPqykC4cXz_yr1BPPP_vVMpg4TAw28_dM0Y565aUc7_ShbA0?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>HTTP method dropdown</p></figcaption></figure>

<mark style="color:blue;">**Đi qua captcha ("Using captcha"):**</mark> A checkbox to indicate if captcha verification is required for the API call. Prevent bot purpose.

<mark style="color:blue;">**Phân quyền ("Permission"):**</mark> Users click on “Phân quyền” to select the available roles to limit the type of user access to the API.

<mark style="color:blue;">**Ignore Roles ("Ignore Roles"):**</mark> defines a field that can be hidden by certain roles.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd80tGhedx5UEna19NUTV2i8B0eR8SmqWIE1sHhMG14UEKAgaGzPqCbLTrviYgEeYOPfZvTjCpwg5W6iu9OiIhQqLYhhVdvTAYYg7A_uYBFavFXM9X8Fi7nyxEJ9fq699-Mer8VRx93bsOpUW8OActBGYH61LBtmcRfpIVvK1tesZloXWSHBfo?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Ignore roles setting</p></figcaption></figure>

<mark style="color:blue;">**Tuỳ chọn gửi lên \["options"]:**</mark> This field is useful for POST, or PUT methods. If the HTTP method is PUT, POST, or PATCH. Users can define a pair of key-value that they want to send in the Request Body.&#x20;

* For example: Key is “description”, Value is “hello world” , it means that you send a request with a body request like that   <mark style="color:orange;">**{“description”: “hello world”}**</mark>.

<mark style="color:blue;">**Tuỳ chọn cập nhật \["criterias"]:**</mark> The user can define more “where” conditions for the API, you must provide a pair of key-value to use this function.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfNtwCFPv_167m_E3oHpGFrhZGsPy6PCYfNXqQdQhgt0P2Vf06Yq8g338FWa7FNUHw6Y7bjmh3Dr6LpVaQTPsICcHMRdjxe-XV8fZesGu1Sz0gZjtmUW_k9GBKPrsEf0hcG_BxAI6Bv4adAgEL5rHIERxhaeCjKn8jFll1RDNYl9Hw1_-ivhjY?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Options and criteria setting</p></figcaption></figure>

<mark style="color:blue;">**Dữ liệu gửi lên ("Request Fields"):**</mark> Specify which fields are required to be submitted

<mark style="color:blue;">**Dữ liệu Hạn chế gửi lên \["Restrict data upload(restrict field)"]:**</mark> Users can define a list of fields that they want to ignore when sending the form.

<mark style="color:blue;">**Dữ liệu trả về ("Response Fields"):**</mark> You can define the fields you want returned.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd9S_WZx4hASCe48WH3b8AjP1ysC1L33ZDoL9gXJd015hoNh5PQsCrNV2fRKfWo0g9H4icJN5fGFUXv3eYw-iI0c7WhQzgXgJwe8iZy1MjKt6VeWxFj_czXiglhVBm4qExjMRtRwgdUld4DT1wQBN96ps3lT8gKyeggXwlwkdkke4Y1XNMFhcc?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Customize data when sending forms or fetching API</p></figcaption></figure>

<mark style="color:blue;">**Query:**</mark> Additional query variable, Ex: \&abc=cd\&ef=gh

<mark style="color:blue;">**Bool Expression:**</mark> Expression to calculate API access based on user information and uploaded data.

* To see more syntax: Click [here](../references/expression.md).

Note: If you completed creating an API. The new API will show on "Hàm tải dữ liệu".

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXebe4LXvLJlv_oAC1n31YnIaRF_EVp5b1tVu23m3SzkezYqGtH5X3CN_rDZegp7vm5uDDkS7B_LW30WxolfGgN03XnfGKfHz391qO03FQWNP5rLAymP4cKrN0BjHfnmXwm5yXFRP-4-J1UdGH6nyVbG0KQHTEtQeKg_QMdattvH3M7loEBwmbs?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Select API for access the page</p></figcaption></figure>

**Step 3:** Click on the “Update” button.
