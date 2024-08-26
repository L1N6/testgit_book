# Activate button

**Solution 1:** select “api”

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXc7b3rbX5g4zlpHnmhyErmnv94lFoLrneMJwEaTM4pwbeWEbw9eAMaRoCQszRBMGsJ7o9ohOxsG9YCFOoH_KMtPz6trcYWMCIZX8P1hAgbXN4lhPvbAISnRI0Z1JJTqhorXgCk84pnZBjcqVciJrKZ8jRcQBZcS6_v8K8AkAcnnV7r2bfg0Lg?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Activate by calling the API setting</p></figcaption></figure>

* <mark style="color:blue;">**Dữ liệu nhúng:**</mark> Embed in request body
* <mark style="color:blue;">**Gọi hàm:**</mark> API that you defined from tab API

**Solution 2:** select “url”

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdqx_fJHvu5vQHgjXNUt4BY1bMEP9M_6EX_YGMhcD1SYU6ciKh8sIpU7uw6rRhZ1Vtb89QQEUippfbkJ1y3IKvgHkHILeMD9WCGuXSIj3SoqIRUNrn21EMH9X5GOV9Z6NLCozHdYRwk58ZDR9FqO1n7SaVI1c8vBEsLoznJHQntuW7OiejNEw?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Activate by redirect URL setting</p></figcaption></figure>

* <mark style="color:blue;">**Chuyển hướng:**</mark> URL to another page.

```
/list/?page=1
/pageEditor?mode=create
/pageEditor?mode=edit&id=$
/form?page=9&mode=create
/form?page=19&mode=edit&id=12

```

<mark style="color:blue;">**"$"**</mark>** notation:** get id of the current record in the row.

**Solution 3:** Select “form popup”

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXew3Fjy_i-zyHDzbN72yfGgCLQkWq21gyX8QANyeP3DtSJ_W5IYpHlBYLTs5xMIQBqk8jx98Wr6mHiS3Atmlao8W4U0j2PluU_L8lvnKQaSMr7j37GWDHF4DVyycZu29RnsE7y-LysxAAUBbUqmf4YMXa-3aGFS38ZTF97a0CqTbtFyNVXy2Xs?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption><p>Activate by open a form popup setting</p></figcaption></figure>

Dữ liệu nhúng:  Data embedded in the form.

`{"page": 2, "mode": "edit", "id":#id#}`  &#x20;

`{"page": 2, "mode":"create"}`  &#x20;

`{"page": 2, "mode":"create","embed":"{\"userId\":#id#}"}`&#x20;

`{"page": 2, "mode":"create","embed":"{\"userId\":#id#,\"id\":#id#}"}`

<mark style="color:blue;">**#id#**</mark> notation: get id of the current record in the row.

<mark style="color:blue;">**"embed":"{\\"userId\\":#id#}"**</mark>:  embed data to the form and the form will send a request with userId attribute in the body request.
