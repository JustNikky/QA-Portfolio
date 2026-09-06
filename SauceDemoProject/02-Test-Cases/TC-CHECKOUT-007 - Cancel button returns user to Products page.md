## TC-CHECKOUT-007 - Cancel button returns user to Products page
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CHECKOUT-007 |
| **Test type** | Functional |
| **Title** | Cancel button returns user to Products page |
| **Module** | Checkout |
| **Priority** | Medium |
| **Preconditions** | User is logged in, has at least one product in the cart, and is on the Checkout Information page. |
| **Test data** | Product: `Sauce Labs Backpack` |
| **Steps** | 1. Open the cart.<br><br>2. Click the `Checkout` button.<br><br>3. Verify that the Checkout Information page is displayed.<br><br>4. Click the `Cancel` button.<br><br>5. Observe the page that is displayed. |
| **Expected result** | The user is redirected from the Checkout Information page to the Products page. |
| **Actual result** | The user was successfully redirected from the Checkout Information page to the Products page. |
| **Status** | **PASS** |
| **Defect** | N/A |
