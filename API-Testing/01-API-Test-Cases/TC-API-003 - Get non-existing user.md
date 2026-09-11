## TC-API-003 - Get non-existing user
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-API-003 |
| **Test type** | Negative |
| **Title** | Get non-existing user |
| **Module** | Users API |
| **Priority** | Medium |
| **Preconditions** | API is available. |
| **Test data** | API: `JSONPlaceholder`<br>Base URL: `https://jsonplaceholder.typicode.com`<br>Endpoint: `/users/999`<br>User ID: `999` |
| **Steps** | 1. Send a **GET** request to `/users/999`.<br><br>2. Verify that the response status code is `404 Not Found`.<br><br>3. Verify that no user data is returned. |
| **Expected result** | The API returns `404 Not Found` and no user data is returned for the non-existing user. |
| **Actual result** | The API returned `404 Not Found` and no user data was returned. |
| **Status** | **PASS** |
| **Defect** | N/A |
