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
On the payment page, when a user updates their address, the system first displays “Address saved” confirmation. Immediately after, it incorrectly shows another message — “Your PayPal information saved” — even though no PayPal email has been entered in the textbox. This can confuse users and create false assumptions that their PayPal details are saved without input.

## 🔁 Steps to Reproduce


## ❌ Actual Result
After updating the address, system displays both messages — “Address saved” and “Your PayPal information saved” — even when no PayPal email has been entered.

## ✅ Expected Result
Only the “Address saved” message should appear when updating the address. The “Your PayPal information saved” message should only appear when a valid PayPal email is entered and saved.

## 📎 Evidence (Screenshot/Video URI)

