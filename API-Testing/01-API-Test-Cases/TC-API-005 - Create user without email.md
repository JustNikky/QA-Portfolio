## TC-API-005 - Create user without email
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-API-005 |
| **Test type** | Negative |
| **Title** | Create user without email |
| **Module** | Users API |
| **Priority** | High |
| **Preconditions** | API is available and `email` is a required field for creating a user. |
| **Test data** | API: `JSONPlaceholder`<br>Base URL: `https://jsonplaceholder.typicode.com`<br>Endpoint: `/users/`<br>Request body:<br>```json<br>{<br>  "name": "Anna Nováková",<br>  "username": "annanovakova"<br>}<br>``` |
| **Steps** | 1. Send a **POST** request to `/users/` without the required `email` field.<br><br>2. Verify that the request is rejected.<br><br>3. Verify that an appropriate validation error is returned. |
| **Expected result** | The API rejects the request and returns an appropriate validation error because the required `email` field is missing. |
| **Actual result** | The API returned `201 Created` and accepted the request even though the `email` field was missing. |
| **Status** | **FAIL** |
| **Defect** |  BUG-API-01 – JSONPlaceholder does not enforce required-field validation. |
