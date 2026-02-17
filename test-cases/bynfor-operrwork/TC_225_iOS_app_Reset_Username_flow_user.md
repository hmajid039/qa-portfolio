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
In the iOS app Reset Username flow, when the user selects Phone Number as the recovery method, the country code field is missing. Even when the user manually includes the country code along with a valid phone number, the app incorrectly displays an “Invalid phone number” error message. This prevents the user from proceeding with username recovery via phone.

## 🔁 Steps to Reproduce
1. Open the iOS app. 2. Go to the Login page. 3. Tap Forgot Username/Password → select Forgot Username. 4. Choose Phone Number as the recovery option. 5. Try to enter a valid phone number (with or without manually typing the country code). 6. Tap Continue.


## ❌ Actual Result
1. Country code field is missing.
2. Even when the user adds the country code manually, an “Invalid phone number” error appears, and the process cannot continue.

## ✅ Expected Result
1. A country code selector (e.g., +91, +1) should be displayed before the phone number input field.
2. The system should validate correctly formatted phone numbers including country code and allow users to proceed if the number is valid.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1WUTpN6_ZpHMwHem9X6NR-S8WF1VllfGJ/view?usp=sharing

