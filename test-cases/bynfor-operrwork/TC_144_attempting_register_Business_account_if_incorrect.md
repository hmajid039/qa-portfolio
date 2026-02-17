**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop/Windows 11
**Date:** 2025-10-16 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When attempting to register a Business account, if an incorrect CAPTCHA value is entered, the system displays a generic error message “Entered random text is incorrect!”. This message does not clearly specify that the CAPTCHA input is invalid. Additionally, the error message appears at the top of the page without automatically scrolling into view, which can cause users to miss it.

## 🔁 Steps to Reproduce
1. Navigate to the Registration page.   2. Select Business account type.   3. Fill in all mandatory fields with valid data.   4. Enter an incorrect CAPTCHA value intentionally.   5. Click on the Register button.


## ❌ Actual Result
The message “Entered random text is incorrect!” is displayed at the top of the page, and the page does not scroll up automatically. The user may not notice the message.

## ✅ Expected Result
The error message should be more specific (e.g., “Incorrect CAPTCHA entered. Please try again.”) and the page should automatically scroll up to bring the message into view.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1dbYjN2H-n5LVzN7_DPFEs8DtH-XhvEX0/view?usp=drive_link

