## TC-CHECKOUT-001 - Checkout accepts valid customer information
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CHECKOUT-001 |
| **Test type** | Functional |
| **Title** | Checkout accepts valid customer information |
| **Module** | Checkout |
| **Priority** | High |
| **Preconditions** | User is logged in, has at least one product in the cart, and is on the Checkout Information page. |
| **Test data** | First Name: `Jane`<br><br>Last Name: `Doe`<br><br>ZIP/Postal Code: `76325`  |
| **Steps** | 1. Enter `Jane` into the First Name field.<br><br>2. Enter `Doe` into the Last Name field.<br><br>3. Enter `76325` into the ZIP/Postal Code field.<br><br>4. Click the `Continue` button.<br><br>5. Observe the page that is displayed.  |
| **Expected result** | The checkout form accepts the valid customer information. The user is successfully redirected to the Checkout Overview page. No validation error messages are displayed. |
| **Actual result** | The checkout form accepted the valid customer information. The user was successfully redirected to the Checkout Overview page. No validation error messages were displayed. |
| **Status** | **PASS** |
| **Defect** | N/A |
