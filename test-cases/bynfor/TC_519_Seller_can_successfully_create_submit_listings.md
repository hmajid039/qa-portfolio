**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-12-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
Seller can successfully create and submit listings priced beyond 999999.99, and admin can approve them without any issue. However, when a buyer tries to add the same high-value listing to the cart, the system displays the error: “The total amount should not be more than 999999.99”.

## 🔁 Steps to Reproduce
1. Go to BynFor and log in (Account: qacomet3) 2. Create a listing priced beyond 999999.99 3. Save and submit the listing → Admin approves it successfully 4. Log in with another user account 5. Try adding the approved high-value listing to the cart


## ❌ Actual Result
Cart displays an error: “The total amount should not be more than 999999.99” and does not allow the item to be added.

## ✅ Expected Result
Cart should accept listings of any approved price, including amounts beyond 999999.99, without showing errors.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1cHnxAkL7T57LG8OqnNl5PTuG80h25lvW/view?usp=sharing

