**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 2026-01-06 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While sending a request in the BynFor Android app, the request is accepted even when the user does not select or check the “I agree with Terms and Conditions” option.

## 🔁 Steps to Reproduce
1. Login to the BynFor Android app 2. Navigate to send a request 3. Do not check/select “I agree with Terms and Conditions” 4. Submit the request


## ❌ Actual Result
The request is successfully submitted and accepted without agreeing to the Terms and Conditions.

## ✅ Expected Result
The request should not be submitted unless the user checks and agrees to the Terms and Conditions. The system should show a validation message if the checkbox is not selected.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1oI66OJ5DuapUT99K49LNqglKzmuKoVvx/view?usp=drive_link

