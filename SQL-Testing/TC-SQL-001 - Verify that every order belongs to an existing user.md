## TC-SQL-001 - Verify that every order belongs to an existing user
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-SQL-001 |
| **Test type** | Data Integrity |
| **Title** | Verify that every order belongs to an existing user |
| **Priority** | High |
| **Preconditions** | `Users` and `Orders` tables contain test data |
| **SQL query** | `SELECT Orders.OrderID, Orders.UserID, Orders.ProductName, Orders.Amount FROM Orders LEFT JOIN Users ON Orders.UserID = Users.UserID WHERE Users.UserID IS NULL;` |
| **Steps** | 1. Execute the SQL query |
| **Expected result** | The query returns no records. Every order has a corresponding user.|
| **Actual result** | No records returned. |
| **Status** | **PASS** |
| **Defect** | N/A |
