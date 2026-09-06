## TC-CHECKOUT-004 - Error displayed when Postal Code is empty
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CHECKOUT-004 |
| **Test type** | Negative |
| **Title** | Error displayed when Postal Code is empty |
| **Module** | Checkout |
| **Priority** | High |
| **Preconditions** | User is logged in, has at least one product in the cart, and is on the Checkout Information page. |
| **Test data** | First Name: `Jane` <br><br>Last Name: `Doe`<br><br>ZIP/Postal Code: ``  |
| **Steps** | 1. Enter `Jane` into the First Name field.<br><br>2. Enter `Doe` into the Last Name field.<br><br>3. Leave the `ZIP/Postal Code` field empty.<br><br>4. Click the `Continue` button.<br><br>5. Observe the page that is displayed.  |
| **Expected result** | The user cannot proceed to the Checkout Overview page. An error message is displayed indicating that the Postal Code is required. |
| **Actual result** | The user could not proceed to the Checkout Overview page. An error message indicating that the Postal Code is required was displayed. |
| **Status** | **PASS** |
| **Defect** | N/A |
