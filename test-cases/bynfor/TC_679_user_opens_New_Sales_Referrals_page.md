**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2026-01-06 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When the user opens the New Sales Referrals page, a validation error message “Effective time to must be greater than current time” is displayed below the field by default, even though the user has not entered any value. This validation message should appear only after an invalid input is provided.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet1) 2. Navigate to Sales Referrals 3. Open New Sales Referral page


## ❌ Actual Result
The validation error message “Effective time to must be greater than current time” is displayed immediately below the field on page load.

## ✅ Expected Result
The validation error should appear only after the user enters an invalid value (effective time less than or equal to current time).

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1mXs-b-DIkltfgAdS7tEJ3NbYmdDAfQRJ/view?usp=sharing

