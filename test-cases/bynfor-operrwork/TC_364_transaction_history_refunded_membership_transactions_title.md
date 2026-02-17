**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Payments

---

## 🐞 Description
In the transaction history for refunded membership transactions, the title appears as a raw internal key (sum_account.sum_acc_transaction_history.UPDATE_INCOME_FROM_ADMIN). This suggests the system is showing a backend identifier instead of a properly mapped, user-friendly label

## 🔁 Steps to Reproduce
1. Log in as a business (majidbusiness, Sun@Ray123) on the bynfor website 2. Go to My Account → Membership 3. Purchase a membership 4. Cancel the membership. 5. Open Transaction History and observe the refund transaction entry


## ❌ Actual Result
The title of the transaction displays as sum_account.sum_acc_transaction_history.UPDATE_INCOME_FROM_ADMIN instead of a human-readable message

## ✅ Expected Result
The transaction title should show a clear, user-friendly label such as “Refund issued by admin” or “Membership refund processed

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1MeU76sXLjYbHkmbHS8CdD9fAiZvAROmP/view?usp=sharing

