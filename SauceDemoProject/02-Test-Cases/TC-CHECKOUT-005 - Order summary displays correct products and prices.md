## TC-CHECKOUT-005 - Order summary displays correct products and prices
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CHECKOUT-005 |
| **Test type** | Functional |
| **Title** | Order summary displays correct products and prices |
| **Module** | Checkout |
| **Priority** | High |
| **Preconditions** | User is logged in, has products in the cart, has entered valid checkout information, and is on the Checkout Overview page. |
| **Test data** | `Sauce Labs Backpack` and `Sauce Labs Bike Light`  |
| **Steps** | 1. Add `Sauce Labs Backpack` and `Sauce Labs Bike Light` to the cart.<br><br>2. Open the cart and click the `Checkout` button.<br><br>3. Enter valid First Name, Last Name, and ZIP/Postal Code information.<br><br>4. Click the `Continue` button.<br><br>5. Verify the products displayed in the Order Summary.<br><br>6. Verify the price displayed for each product. |
| **Expected result** | The Order Summary displays all products that were added to the cart. Each product has the correct name and price matching the product information displayed on the Products page. |
| **Actual result** | The Order Summary displayed all products that were added to the cart. Each product had the correct name and price matching the product information displayed on the Products page. |
| **Status** | **PASS** |
| **Defect** | N/A |
