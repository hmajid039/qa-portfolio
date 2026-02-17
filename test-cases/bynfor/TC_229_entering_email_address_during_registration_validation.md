**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android 15
**Date:** 2025-10-28 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When entering an email address during registration, the validation error message (“Please enter a valid email address”) is displayed too early — even before the user finishes typing a valid email. The error message should appear only after the user completes the field or moves focus away from it.

## 🔁 Steps to Reproduce
1. Open the Android app. 2. Go to the Register page 3.Click on the Email Address field. 4..Start typing a valid email 5.Observe that the error message “Please enter a valid email address” appears before completing the email.


## ❌ Actual Result
The validation error appears prematurely while the user is still typing a valid email.

## ✅ Expected Result
The error message should only appear when the field is left empty, or when the user finishes typing and moves focus away with an invalid email format.

## 📎 Evidence (Screenshot/Video URI)

