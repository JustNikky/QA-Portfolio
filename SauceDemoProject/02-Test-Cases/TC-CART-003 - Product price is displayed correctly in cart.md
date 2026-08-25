## TC-CART-003 - Product price is displayed correctly in cart
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CART-003 |
| **Test type** | Functional |
| **Title** | Product price is displayed correctly in cart |
| **Module** | Cart |
| **Priority** | High |
| **Preconditions** | User is on the SauceDemo Products page after successful login. No product has been added to the cart. |
| **Test data** | `Sauce Labs Backpack` - `$29.99` |
| **Steps** | 1. Locate the `Sauce Labs Backpack` product.<br><br>2. Verify that the product price is `$29.99`.<br><br>3. Click **Add to cart**.<br><br>4. Click the **Cart** icon.<br><br>5. Verify that the price displayed for the `Sauce Labs Backpack` is `$29.99`. |
| **Expected result** | The `Sauce Labs Backpack` is displayed in the cart with the correct price of `$29.99`. |
| **Actual result** | The `Sauce Labs Backpack` was displayed in the cart with the correct price of `$29.99`. |
| **Status** | **PASS** |
| **Defect** | N/A |
