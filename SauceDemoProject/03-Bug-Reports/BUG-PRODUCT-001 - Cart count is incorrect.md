## BUG-PRODUCT-001 - Cart count is incorrect

---

| **Field** | **Value** |
|---|---|
| **Bug ID** | BUG-PRODUCT-001 |
| **Title** | Cart count is incorrect |
| **Related test case** | TC-PRODUCT-005 |
| **Module** | Product |
| **Severity** | Medium |
| **Priority** | Medium |
| **Environment** | SauceDemo web application |
| **Preconditions** | User is on the SauceDemo login page. |
| **Steps to reproduce** | 1. Enter `standard_user` into the Username field.<br><br>2. Enter `secret_sauce` into the Password field.<br><br>3. Click **Login**. <br><br>4. Verify the cart indicator. |
| **Expected result** | The cart count should display 0 or should not be displayed when the cart is empty. |
| **Actual result** | The cart indicator displays 1 immediately after login even though the cart is empty. After adding one product to the cart, the indicator increases to 2 even though only one product is present in the cart. |
| **Status** | Open |
| **Defect type** | Functional |
| **Description** | The cart indicator displays 1 immediately after login even though the cart is empty. After adding one product to the cart, the indicator increases to 2 even though only one product is present in the cart. The product is successfully added to the cart, but the cart indicator displays an incorrect count. |
