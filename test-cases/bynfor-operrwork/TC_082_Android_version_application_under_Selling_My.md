**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Responsive Design Bug
**Date:** 2025-07-13 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the Android version of the application, under Selling → My Store, the Send OTP button appears only when the user selects the USA (+1) country code.
For any other country code, the Send OTP option disappears, preventing users from verifying phone numbers outside the USA. This limits functionality and affects international users.

## 🔁 Steps to Reproduce
1. Open the application on an Android device. 2. Navigate to Selling → My Store. 3. In the phone number field, select USA (+1) as the country code. 4. Observe that the Send OTP button is visible. 5. Change the country code to any other (e.g., India, UK, Canada). 6. Observe that the Send OTP button disappears.


## ❌ Actual Result
Send OTP button is visible only for USA phone numbers.

Disappears for all other country codes.

## ✅ Expected Result
Send OTP functionality should work for all supported country codes.

Button should remain visible regardless of the selected country code.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1yAbgkS11epkXT-UbD4kLs20N5fqhJxZD/view?usp=sharing

