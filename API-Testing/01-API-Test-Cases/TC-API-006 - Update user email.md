## TC-API-006 - Update user email
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-API-006 |
| **Test type** | Functional |
| **Title** | Update user email |
| **Module** | Users API |
| **Priority** | High |
| **Preconditions** | API is available and user with ID `5` exists. |
| **Test data** | API: `JSONPlaceholder`<br>Base URL: `https://jsonplaceholder.typicode.com`<br>Endpoint: `/users/5`<br>Request body:<br>```"email": "new.email@test.cz"``` |
| **Steps** | 1. Send a **PATCH** request to `/users/5` with the updated email address.<br><br>2. Verify that the response status code is `200 OK`.<br><br>3. Verify that the response contains the updated email address. |
| **Expected result** | The API returns `200 OK` and the user's email is updated to `new.email@test.cz` in the response. |
| **Actual result** | The API returned `200 OK` and the response contained the updated email address `new.email@test.cz`. |
| **Status** | **PASS** |
| **Defect** | N/A |
