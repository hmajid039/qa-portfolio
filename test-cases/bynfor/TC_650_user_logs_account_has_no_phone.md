**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-12-31 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a user logs in with an account that has no phone number, the Become a Partner page incorrectly shows the Send OTP button after selecting a country other than USA. The OTP option should appear only for USA. When the user switches the country again, the Send OTP button disappears.

## 🔁 Steps to Reproduce
1. Go to BynFor dev and log in with an account without a phone number(qacomet44) 2. Navigate to Become a Partner page 3. Select a country other than USA 4. Observe the Send OTP button 5. Switch the country again


## ❌ Actual Result
The Send OTP button appears for a non-USA country and then disappears after switching the country again.

## ✅ Expected Result
The Send OTP button should be displayed only when USA is selected and should not appear for other countries.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/18EXrZ_TmW6U2-YZ-cy32hH6BfOii8Z9R/view?usp=sharing

