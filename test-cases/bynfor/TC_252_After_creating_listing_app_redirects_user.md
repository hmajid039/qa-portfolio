**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-29 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
After creating a listing, the app redirects the user to the Personal Information page. On this page, the phone number input field allows users to enter excessively long numbers (up to 22–23 digits) without any validation or restriction. This can lead to invalid contact information being saved in the system.

## 🔁 Steps to Reproduce


## ❌ Actual Result
The phone number field accepts up to 22–23 digits without validation or warning.

## ✅ Expected Result
The phone number field should restrict input to a valid length  and show an error if the limit is exceeded.

## 📎 Evidence (Screenshot/Video URI)

