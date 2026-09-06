## TC-CART-008 - User can proceed to checkout from cart
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CART-008 |
| **Test type** | Functional |
| **Title** | User can proceed to checkout from cart |
| **Module** | Cart |
| **Priority** | High |
| **Preconditions** | User is logged in and has at least one product added to the cart. |
| **Test data** | `Sauce Labs Backpack` |
| **Steps** | 1. Open the cart.<br><br>2. Verify that `Sauce Labs Backpack` is present in the cart.<br><br>3. Click the `Checkout` button.<br><br>4. Observe the page that is displayed. |
| **Expected result** | The user is successfully redirected from the Cart page to the Checkout Information page. The checkout form is displayed and contains fields for First Name, Last Name, and ZIP/Postal Code. |
| **Actual result** | The user was successfully redirected from the Cart page to the Checkout Information page. The checkout form was displayed with fields for First Name, Last Name, and ZIP/Postal Code. |
| **Status** | **PASS** |
| **Defect** | N/A |
