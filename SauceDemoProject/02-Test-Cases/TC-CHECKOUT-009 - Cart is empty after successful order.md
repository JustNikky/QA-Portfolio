## TC-CHECKOUT-009 - Cart is empty after successful order
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CHECKOUT-009 |
| **Test type** | Functional |
| **Title** | Cart is empty after successful order |
| **Module** | Checkout |
| **Priority** | High |
| **Preconditions** | User is logged in, has at least one product in the cart, and is on the Checkout Overview page with valid checkout information entered. |
| **Test data** |  Product: `Sauce Labs Backpack`<br><br>First Name: `Jane`<br><br>Last Name: `Doe`<br><br>ZIP/Postal Code: `76325`   |
| **Steps** | 1. Verify that `Sauce Labs Backpack` is present in the cart.<br><br>2. Complete the checkout process by clicking the `Finish` button.<br><br>3. Verify that the order confirmation page is displayed.<br><br>4. Open the cart.<br><br>5. Observe the contents of the cart. |
| **Expected result** | The order is successfully completed and the user is redirected to the order confirmation page. The cart is empty after the order is placed, and no previously purchased products are displayed. |
| **Actual result** | The order was successfully completed and the user was redirected to the order confirmation page. The cart was empty after the order was placed, and no previously purchased products were displayed. |
| **Status** | **PASS** |
| **Defect** | N/A |
