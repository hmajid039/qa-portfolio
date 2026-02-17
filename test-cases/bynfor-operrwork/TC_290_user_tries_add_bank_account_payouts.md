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
When the user tries to add a bank account for payouts using Routing Number 110000000 and Account Number 000111111116, the system shows an unclear error message — “Status code did not fall within given range.” This message is not user-friendly and doesn’t specify the real reason for the failure (e.g., invalid account, closed account, etc.).

## 🔁 Steps to Reproduce
1. Go to BynFor app and log In (Account: qacomet2) 2. Navigate to Payment Section → Bank Account Information 3. Click on Add Bank Account 4. Enter Routing Number: 110000000 and Account Number: 000111111116 5. Click Save / Continue


## ❌ Actual Result
An unclear system error appears — “Status code did not fall within given range.”

## ✅ Expected Result
A clear, user-friendly message should appear explaining the issue (e.g., “Account not found” or “Invalid bank account details”). The system should handle HTTP errors gracefully.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1Kblhf2_r4MfvSIUe-dnU2omVjXGKeVHR/view?usp=sharing

