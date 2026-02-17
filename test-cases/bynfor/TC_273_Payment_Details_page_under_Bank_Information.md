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
On the Payment Details page under Bank Information, when the user enters a valid routing number but an account number that does not have debit authorization enabled, the system still shows a success message after saving. This indicates that the validation for debit authorization is missing or not working properly.

## 🔁 Steps to Reproduce


## ❌ Actual Result
The system displays a success message — “Bank information saved successfully.”

## ✅ Expected Result
The system should show an error message such as “Debit not authorized” and prevent saving the bank information.

## 📎 Evidence (Screenshot/Video URI)

