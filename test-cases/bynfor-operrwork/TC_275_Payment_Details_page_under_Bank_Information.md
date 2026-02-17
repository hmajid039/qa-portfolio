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
On the Payment Details page under Bank Information, when a user enters a valid routing number but a bank account with insufficient funds, the system still shows a success message — “Bank information saved successfully.” This indicates that the system is missing a backend validation check for account balance during the verification process.

## 🔁 Steps to Reproduce


## ❌ Actual Result
The system displays “Bank information saved successfully,” even though the linked account has insufficient funds.

## ✅ Expected Result
The system should show an error message such as “Insufficient funds. Please use an active bank account with available balance.” and prevent saving the account information.

## 📎 Evidence (Screenshot/Video URI)

