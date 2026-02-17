**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-07-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When selecting “United States” as country and entering an invalid/incomplete number (e.g., 1(243)564), the validation error flashes for a split second and disappears. For other countries, the “Save Changes” button works or behaves differently. And send otp is displayed for US only

## 🔁 Steps to Reproduce
1. Go to My Account(majidbusiness, Sun@Ray123) 2. Select country as United States for phone number 3. Enter phone number 1(23)564 4. Click Save Changes 5. Observe error behavior 6. Repeat with another country (e.g., UK)


## ❌ Actual Result
Error message appears and disappears instantly for US, while for other countries the validation behaves differently and "send otp" does not display

## ✅ Expected Result
Validation message should remain visible to be read and should behave consistently across countries

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1OKW0wXTB0_ZGk5-Dp82piaYGt80Vsu-S/view?usp=sharing

