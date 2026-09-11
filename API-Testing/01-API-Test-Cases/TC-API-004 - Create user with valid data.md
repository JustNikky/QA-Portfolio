## TC-API-004 - Create user with valid data
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-API-004 |
| **Test type** | Functional |
| **Title** | Create user with valid data |
| **Module** | Users API |
| **Priority** | High |
| **Preconditions** | API is available and accepts POST requests for creating users. |
| **Test data** | API: `JSONPlaceholder`<br>Base URL: `https://jsonplaceholder.typicode.com`<br>Endpoint: `/users/`<br>Request body:<br>```"name": "Niky QA",<br>  "username": "nikyqa",<br>  "email": "niky.qa@test.cz"``` |
| **Steps** | 1. Send a **POST** request to `/users/` with valid user data.<br><br>2. Verify that the response status code is `201 Created`.<br><br>3. Verify that the response contains the submitted user data.<br><br>4. Verify that a user ID is returned in the response. |
| **Expected result** | The API returns `201 Created` and the response contains the submitted user data with a generated user ID. |
| **Actual result** | The API returned `201 Created` and the response contained the submitted user data with generated user ID `11`. |
| **Status** | **PASS** |
| **Defect** | N/A |
