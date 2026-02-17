**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-06 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Payments

---

## 🐞 Description
On the Checkout page, users can edit the shipping address. The address textbox displays an error message: “Invalid address. Only alphabets and special characters are allowed.” However, the field does not actually accept any special characters and continues to show the error.

## 🔁 Steps to Reproduce
1. Go to Bynfor(Account used: qacomet2) 2. Go to Checkout page. 3. Click on the option to edit the shipping address. 4. Enter an address containing special characters (e.g., commas, hyphens, #, /). 5. Observe the error displayed in the address textbox


## ❌ Actual Result
The address field shows “Invalid address” error and does not accept any special characters, even though the error message suggests they are allowed.

## ✅ Expected Result
Either:

The address field should accept valid special characters (commas, hyphens, #, /, etc.) without showing an error.
OR

Update the error message to remove “special characters are allowed” so it accurately reflects the validation rules.

## 📎 Evidence (Screenshot/Video URI)
https://livestore.operrwork.com/operrwork/video/2025__11/2025_11_6__18_4_55__Operr1762452293518.webm

