**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-31 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When attempting to save a PayPal account, the confirmation popup incorrectly displays a message related to the address instead of the PayPal account.
The popup says: “Are you sure this is the correct address ‘Bahria Town, Lahore, Punjab 54740’?”
This message is misleading because the action being performed is to save a PayPal account, not an address. And after clicking OK, two toast messages appear , one related to the address and another to the account.
All popups and toast notifications should be related only to the PayPal account action.

## 🔁 Steps to Reproduce


## ❌ Actual Result
The confirmation popup shows an address-related message and two toasts appear (address + account).

## ✅ Expected Result
A confirmation popup and toast message should appear only for saving the PayPal account, not for the address.

## 📎 Evidence (Screenshot/Video URI)

