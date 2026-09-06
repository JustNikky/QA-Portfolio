## TC-CART-007 - Cart preserves added products when navigating away and back
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CART-007 |
| **Test type** | Functional |
| **Title** | Cart preserves added products when navigating away and back |
| **Module** | Cart |
| **Priority** | High |
| **Preconditions** | User is logged in and is on the Products page. |
| **Test data** | `Sauce Labs Backpack`, `Sauce Labs Bike Light` |
| **Steps** | 1. Click Add to cart for `Sauce Labs Backpack`.<br><br>2. Click Add to cart for `Sauce Labs Bike Light`.<br><br>3. Open the cart.<br><br>4. Observe the products in the cart. |
| **Expected result** | The cart preserves the previously added products after navigating away and back. `Sauce Labs Backpack` and `Sauce Labs Bike Light` are still present in the cart with the correct quantities. The cart badge displays the correct number of items (2). |
| **Actual result** | The cart preserved the previously added products after navigating away and back. `Sauce Labs Backpack` and `Sauce Labs Bike Light` were still present in the cart with the correct quantities. The cart badge displayed the correct number of items (2). |
| **Status** | **PASS** |
| **Defect** | N/A |
