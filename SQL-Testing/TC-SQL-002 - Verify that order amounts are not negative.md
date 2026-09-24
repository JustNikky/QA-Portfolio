## TC-SQL-002 - Verify that order amounts are not negative
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-SQL-002 |
| **Test type** | Data Validation |
| **Title** | Verify that order amounts are not negative |
| **Priority** | High |
| **Preconditions** | `Orders` table contains test data |
| **SQL query** | `SELECT OrderID, UserID, ProductName, Amount FROM Orders WHERE Amount < 0;` |
| **Steps** | 1. Execute the SQL query |
| **Expected result** | Query returns no records. All order amounts are 0 or greater. |
| **Actual result** | No records returned. |
| **Status** | **PASS** |
| **Defect** | N/A |
