## TC-API-008 - Delete user
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-API-008 |
| **Test type** | Functional |
| **Title** | Delete user |
| **Module** | Users API |
| **Priority** | High |
| **Preconditions** | API is available and user with ID `5` exists. |
| **Test data** | API: `JSONPlaceholder`<br>Base URL: `https://jsonplaceholder.typicode.com`<br>Endpoint: `/users/5`<br>User ID: `5` |
| **Steps** | 1. Send a **DELETE** request to `/users/5`.<br><br>2. Verify that the response status code is `200 OK`.<br><br>3. Verify that the API indicates a successful deletion. |
| **Expected result** | The API returns `200 OK` and indicates that the user was successfully deleted. |
| **Actual result** | The API returned `200 OK`, indicating a successful deletion. |
| **Status** | **PASS** |
| **Defect** | N/A |
