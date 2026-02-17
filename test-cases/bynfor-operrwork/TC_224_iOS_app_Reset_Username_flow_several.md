**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-28 00:00:00
**Status:** Open
**Severity:** Low
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the iOS app Reset Username flow, several user-facing text strings are incorrect, misspelled, and not user-friendly.

After selecting email to reset the username, the message reads: “please check you email for token” — contains typos and awkward phrasing.

After entering email and tapping Continue, a confirmation popup shows a garbled sentence: “if you continue to have problem accessing your account, please contact your a bynfor administration or us” — contains multiple typos and unclear wording.

## 🔁 Steps to Reproduce
1. Open the iOS app. 2. Go to the Login page. 3. Tap “Forgot Username/Password” → choose Forgot Username. 4. Select Email as the recovery method. 5. Enter a valid registered email and tap Continue. 6. Observe the message shown after selecting email and the confirmation popup after continuing.


## ❌ Actual Result
Message shown: “please check you email for token”. Word token is not layman word

Confirmation popup text: “if you continue to have problem accessing your account, please contact your a bynfor administration or us” (multiple typos and unclear reference “a bynfor administration”).

## ✅ Expected Result
Clear, grammatically correct, and user-friendly copy.
Examples of corrected text:

After selecting email: “Please check your email for a verification code.”

Confirmation popup: “If you continue to have problems accessing your account, please contact your administrator or our support team at Bynfor.com

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1jZ6QIYraquVtTJIGDgfTA0Z14MoZxwcL/view?usp=sharing

