**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-10-06 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
The Username field currently allows users to enter only digits or special characters without any letters. This is not expected behavior, as a valid username should include at least some alphabetic characters.

## 🔁 Steps to Reproduce
1.Go to the registration 2.Enter only digits (e.g., 12345) or only special characters (e.g., !@#$%) in the Username field.


## ❌ Actual Result
The form accepts usernames with only digits or special characters without any error.

## ✅ Expected Result
The Username field should require at least one letter along with digits or special characters. Submitting a username with only digits or special characters should display a validation error.

## 📎 Evidence (Screenshot/Video URI)
https://livestore.operrwork.com/operrwork/video/2025__10/2025_10_6__18_22_36__Operr1759774953414.webm

