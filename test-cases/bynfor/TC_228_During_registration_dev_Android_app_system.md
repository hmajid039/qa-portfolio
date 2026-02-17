**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android 15
**Date:** 2025-10-28 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
During registration on the dev Android app, the system allows users to register successfully even when an invalid  email address is entered (like an email wich dosn't exit). Proper email validation is missing.

## 🔁 Steps to Reproduce
1.Open the Bynfor Dev Android app. 2.Go to the Register / Sign Up page. 3.Enter an invalid email address (e.g. an email address which dosn't exist). 4.Fill in the remaining required fields. 5.Tap Register.


## ❌ Actual Result
The registration completes successfully even though the email address is not valid

## ✅ Expected Result
The system should validate the email address and show an error message (e.g., “Please enter a valid email address”) before allowing registration.

## 📎 Evidence (Screenshot/Video URI)

