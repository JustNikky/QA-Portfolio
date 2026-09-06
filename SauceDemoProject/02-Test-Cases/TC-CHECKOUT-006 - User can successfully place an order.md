## TC-CHECKOUT-006 - User can successfully place an order
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CHECKOUT-006 |
| **Test type** | Functional |
| **Title** | User can successfully place an order |
| **Module** | Checkout |
| **Priority** | High |
| **Preconditions** | User is logged in, has at least one product in the cart, and has entered valid checkout information. |
| **Test data** | Product: `Sauce Labs Backpack`<br><br>First Name: `Jane`<br><br>Last Name: `Doe`<br><br>ZIP/Postal Code: `76325`  |
| **Steps** | 1. Open the cart.<br><br>2. Click the `Checkout` button.<br><br>3. Enter valid First Name, Last Name, and ZIP/Postal Code information.<br><br>4. Click the `Continue` button.<br><br>5. Verify that the product and order information are correct on the Checkout Overview page.<br><br>6. Click the `Finish` button.<br><br>7. Observe the confirmation page. |
| **Expected result** | The order is successfully placed. The user is redirected to the order confirmation page displaying a confirmation message indicating that the order has been successfully placed. |
| **Actual result** | The order was successfully placed. The user was redirected to the order confirmation page displaying a confirmation message indicating that the order was successfully placed. |
| **Status** | **PASS** |
| **Defect** | N/A |
