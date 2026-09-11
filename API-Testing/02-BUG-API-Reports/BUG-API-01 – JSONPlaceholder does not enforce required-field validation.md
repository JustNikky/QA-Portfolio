## BUG-API-01 - JSONPlaceholder does not enforce required-field validation

---

| **Field** | **Value** |
|---|---|
| **Bug ID** | BUG-API-001 |
| **Title** | JSONPlaceholder does not enforce required-field validation |
| **Related test case** | TC-API-005 |
| **Module** | Users API |
| **Severity** | Medium |
| **Priority** | Medium |
| **Environment** | JSONPlaceholder REST API |
| **Preconditions** | API is available and the `email` field is expected to be required when creating a user. |
| **Steps to reproduce** | 1. Send a **POST** request to `/users/`.<br><br>2. Use a request body without the `email` field:<br><br>```json<br>{<br>  "name": "Anna Nováková",<br>  "username": "annanovakova"<br>}<br>```<br><br>3. Send the request. |
| **Expected result** | The API rejects the request and returns an appropriate validation error indicating that the required `email` field is missing. |
| **Actual result** | The API returns `201 Created` and accepts the request even though the required `email` field is missing. |
| **Status** | Open |
| **Defect type** | Functional / Validation |
| **Description** | The API accepts a user creation request without the required `email` field and returns `201 Created`. Missing required-field validation allows incomplete user data to be accepted. |
