**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2026-01-06 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
The Find Username field under Sales Referrals accepts any random or non-existing username without validation, allowing invalid referrals to be added.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet1) 2. Navigate to Sales Referrals 3. Click on Find Username 4. Enter a random/non-existing username (e.g., test123xyz) 5. Submit or proceed


## ❌ Actual Result
The system accepts the random username without any error or validation.. Only once in sequence gave validation errors others did not.

## ✅ Expected Result
The system should validate the username and show an error if the username does not exist.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1kXYZ9d6JO0X0ldap4QBG8N4tbEGNYTT1/view?usp=sharing

