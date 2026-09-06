## TC-CHECKOUT-008 - Order total is calculated correctly
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CHECKOUT-008 |
| **Test type** | Functional |
| **Title** | Order total is calculated correctly |
| **Module** | Checkout |
| **Priority** | High |
| **Preconditions** | User is logged in, has products in the cart, has entered valid checkout information, and is on the Checkout Overview page. |
| **Test data** |  `Sauce Labs Backpack` - `$29.99`<br><br>`Sauce Labs Bike Light` - `$9.99`  |
| **Steps** | 1. Add `Sauce Labs Backpack` and `Sauce Labs Bike Light` to the cart.<br><br>2. Open the cart and click the `Checkout` button.<br><br>3. Enter valid First Name, Last Name, and ZIP/Postal Code information.<br><br>4. Click the `Continue` button.<br><br>5. Verify the Item total displayed on the Checkout Overview page.<br><br>6. Verify the Tax amount.<br><br>7. Verify the Total amount.<br><br>8. Compare the displayed Total with the expected calculation. |
| **Expected result** | The Item total is calculated correctly based on the prices of the selected products. The Tax is calculated correctly. The Total equals the Item total plus the Tax. |
| **Actual result** | The Item total was calculated correctly. The Tax was calculated correctly. The Total matched the Item total plus the Tax. |
| **Status** | **PASS** |
| **Defect** | N/A |
