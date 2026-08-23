## TC-PRODUCT-005 - Product Sauce Labs Backpack can be added to cart
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-PRODUCT-005 |
| **Test type** | Functional |
| **Title** | Product Sauce Labs Backpack can be added to cart |
| **Module** | Product |
| **Priority** | High |
| **Preconditions** | User is on the SauceDemo Products page after successful login. The cart is empty. |
| **Test data** | `Sauce Labs Backpack` |
| **Steps** | 1. Locate product `Sauce Labs Backpack`.  <br><br>2. Click **Add to cart**. <br><br>3. Verify that the cart indicator displays `1`.  |
| **Expected result** | The product is added to the cart. The cart indicator displays `1`. |
| **Actual result** | The cart indicator displayed `1` before the product was added to the cart. |
| **Status** | **FAIL** |
| **Defect** | BUG-PRODUCT-001 |
