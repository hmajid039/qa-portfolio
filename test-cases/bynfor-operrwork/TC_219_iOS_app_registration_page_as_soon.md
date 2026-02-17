**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-28 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the iOS app registration page, as soon as the user starts typing in the email field, the error message “Please enter a valid email address” is displayed prematurely. This causes confusion because the user hasn’t finished typing the email yet.

## 🔁 Steps to Reproduce
1. Open the iOS app. 2. Navigate to the registration page. 3. Tap on the email input field. 4. Start typing an email address .


## ❌ Actual Result
The error message “Please enter a valid email address” appears immediately after typing starts, even before completing the email.

## ✅ Expected Result
The error message should appear only after the user finishes typing and moves out of the field, or after entering an invalid email format.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1fFhF-K-nLnoXUt_CCx9ZT-7OiXkRguzl/view?usp=drive_link

