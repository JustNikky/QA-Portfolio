## TC-API-007 - Update user
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-API-007 |
| **Test type** | Functional |
| **Title** | Update user |
| **Module** | Users API |
| **Priority** | High |
| **Preconditions** | API is available and user with ID `5` exists. |
| **Test data** | API: `JSONPlaceholder`<br>Base URL: `https://jsonplaceholder.typicode.com`<br>Endpoint: `/users/5`<br>Request body:<br>```"name": "Anna Nováková", "email": "anna.new@test.cz", "username": "annanovakova"``` |
| **Steps** | 1. Send a **PUT** request to `/users/5` with the updated user data.<br><br>2. Verify that the response status code is `200 OK`.<br><br>3. Verify that the response contains the updated user data.<br><br>4. Verify that the `name`, `email`, and `username` values match the submitted data. |
| **Expected result** | The API returns `200 OK` and the response contains the updated user data with the submitted `name`, `email`, and `username` values. |
| **Actual result** | The API returned `200 OK` and the response contained the updated `name`, `email`, and `username` values. |
| **Status** | **PASS** |
| **Defect** | N/A |
