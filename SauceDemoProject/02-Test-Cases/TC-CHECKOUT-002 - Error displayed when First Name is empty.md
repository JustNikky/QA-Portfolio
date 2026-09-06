## TC-CHECKOUT-002 - Error displayed when First Name is empty
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-CHECKOUT-002 |
| **Test type** | Negative |
| **Title** | Error displayed when First Name is empty |
| **Module** | Checkout |
| **Priority** | High |
| **Preconditions** | User is logged in, has at least one product in the cart, and is on the Checkout Information page. |
| **Test data** | First Name: `` <br><br>Last Name: `Doe`<br><br>ZIP/Postal Code: `76325`  |
| **Steps** | 1. Leave the `First Name` field empty.<br><br>2. Enter `Doe` into the Last Name field.<br><br>3. Enter `76325` into the ZIP/Postal Code field.<br><br>4. Click the `Continue` button.<br><br>5. Observe the page that is displayed.  |
| **Expected result** | The user cannot proceed to the Checkout Overview page. An error message is displayed indicating that the First Name is required. |
| **Actual result** | The user could not proceed to the Checkout Overview page. An error message indicating that the First Name is required was displayed. |
| **Status** | **PASS** |
| **Defect** | N/A |
