## TC-API-002 - Filter users by website
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-API-002 |
| **Test type** | Functional |
| **Title** | Filter users by website |
| **Module** | Users API |
| **Priority** | Medium |
| **Preconditions** | API is available and users can be filtered by the `website` query parameter. |
| **Test data** | API: `JSONPlaceholder`<br>Base URL: `https://jsonplaceholder.typicode.com`<br>Endpoint: `/users?website=demarco.info`<br>Website: `demarco.info` |
| **Steps** | 1. Send a **GET** request to `/users?website=demarco.info`.<br><br>2. Verify that the response status code is `200 OK`.<br><br>3. Verify that the response contains users matching the requested website.<br><br>4. Verify that each returned user's `website` value is `demarco.info`. |
| **Expected result** | The API returns `200 OK` and the response contains only users whose website matches `demarco.info`. |
| **Actual result** | The API returned `200 OK` and the response contained a user whose website was `demarco.info`. |
| **Status** | **PASS** |
| **Defect** | N/A |
