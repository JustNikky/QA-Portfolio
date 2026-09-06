## TC-CHECKOUT-003 - Error displayed when Last Name is empty
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CHECKOUT-003 |
| **Test type** | Negative |
| **Title** | Error displayed when Last Name is empty |
| **Module** | Checkout |
| **Priority** | High |
| **Preconditions** | User is logged in, has at least one product in the cart, and is on the Checkout Information page. |
| **Test data** | First Name: `Jane` <br><br>Last Name: ``<br><br>ZIP/Postal Code: `76325`  |
| **Steps** | 1. Enter `Jane` into the First Name field.<br><br>2. Leave the `Last Name` field empty.<br><br>3. Enter `76325` into the ZIP/Postal Code field.<br><br>4. Click the `Continue` button.<br><br>5. Observe the page that is displayed.  |
| **Expected result** | The user cannot proceed to the Checkout Overview page. An error message is displayed indicating that the Last Name is required. |
| **Actual result** | The user could not proceed to the Checkout Overview page. An error message indicating that the Last Name is required was displayed. |
| **Status** | **PASS** |
| **Defect** | N/A |
