**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2026-01-06 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While purchasing a product, the system allows the user to proceed with the order even after displaying an error message stating that the entered wallet amount exceeds the available balance. Despite the validation message, no restriction is applied, and the product can be purchased successfully.

## 🔁 Steps to Reproduce
1. Log in to the website  2. Select a product and proceed to checkout. 3. Enter the required purchase details. 4. Enable the Use Wallet Funds option. 5. Enter an amount greater than the available wallet balance. 6. Observe the validation message. 7. Continue and complete the purchase.


## ❌ Actual Result
The system displays a message indicating that the entered amount is out of the wallet balance, but still allows the user to proceed and successfully complete the purchase without any restriction.

## ✅ Expected Result
The system should restrict the user from proceeding with the purchase when the entered wallet amount exceeds the available balance and should disable the checkout process until a valid amount is entered.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1_RsbSylUmgRi26rv8DJwJ_qnQmXQt-v1/view?usp=drive_link

