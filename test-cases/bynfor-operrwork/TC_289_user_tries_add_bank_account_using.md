**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-31 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When the user tries to add a bank account using valid test credentials (Routing Number: 110000000, Account Number: 000123456789), the system fails to complete the process and displays a 404 reading error. This prevents users from verifying or linking their bank accounts successfully.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log In (Account: qacomet2) 2. Navigate to the Payment Method or Bank Account section. 3. Click on Add Bank Account. 4. Enter Routing Number: 110000000 and Account Number: 000123456789. 5. Click Save / Verify.


## ❌ Actual Result
A 404 reading error appears, and the bank account is not added successfully.                                                                         Note: This behaviour is constant with other account numbers.

## ✅ Expected Result
The bank account should be added successfully and proceed with ownership verification without showing any error.

## 📎 Evidence (Screenshot/Video URI)

