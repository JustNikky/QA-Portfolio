## TC-API-001 - Get user by ID
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-API-001 |
| **Test type** | Functional |
| **Title** | Get user by ID |
| **Module** | Users API |
| **Priority** | High |
| **Preconditions** | API is available and user with ID `5` exists. |
| **Test data** | API: `JSONPlaceholder`<br>Base URL: `https://jsonplaceholder.typicode.com`<br>Endpoint: `/users/5`<br>User ID: `5` |
| **Steps** | 1. Send a **GET** request to `/users/5`.<br><br>2. Verify that the response status code is `200 OK`.<br><br>3. Verify that the response contains user data.<br><br>4. Verify that the returned user ID is `5`. |
| **Expected result** | The API returns `200 OK` and the response contains the requested user with ID `5`. |
| **Actual result** | The API returned `200 OK` and the response contained the requested user with ID `5`. |
| **Status** | **PASS** |
| **Defect** | N/A |
