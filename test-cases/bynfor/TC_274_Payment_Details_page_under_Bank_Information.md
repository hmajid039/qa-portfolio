**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-30 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
On the Payment Details page under Bank Information, when a user enters a bank account that is marked as having an invalid currency (i.e., its currency doesn’t match the supported currency of the merchant or payment processor), the system still displays a success message — “Bank information saved successfully.” This indicates that the currency validation check is missing or failing.

## 🔁 Steps to Reproduce


## ❌ Actual Result
The system displays “Bank information saved successfully,” and the account is added — even though the currency is invalid.

## ✅ Expected Result
The system should reject the bank account and display an error message such as “Invalid currency. Please add a bank account in the supported currency.”

## 📎 Evidence (Screenshot/Video URI)

