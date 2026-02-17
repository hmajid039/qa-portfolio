**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android 15
**Date:** 2025-10-29 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a user tries to register using an email address that already exists in the system, the application displays a backend error string (rest.createUser.emailExisted) instead of showing a readable and user-friendly validation message like “This email address is already registered.

## 🔁 Steps to Reproduce
1.Open the Android app. 2.Click on Register. 3..Enter an email address that is already registered with another account. 4.Fill in the remaining required fields. 5.Tap on the Register button.


## ❌ Actual Result
Error displayed: rest.createUser.emailExisted

## ✅ Expected Result
A clear, user-friendly message should be shown like,

“This email address is already registered. Please use a different email .

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1xRnvySaarAwzCsYEWMRUZztbY8u5elFr/view?usp=drive_link

