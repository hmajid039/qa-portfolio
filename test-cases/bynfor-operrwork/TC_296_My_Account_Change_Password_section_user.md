**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-31 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Security

---

## 🐞 Description
In the My Account → Change Password section, the user can enter the same value for the old password, new password, and confirm password fields. The system allows this action without showing any validation error, which compromises password security standards.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet3) 2. Navigate to My Account → Change Password 3. Enter the same password in all three fields – old password, new password, and confirm password 4. Tap on Save/Change Password


## ❌ Actual Result
The system accepts the password change even when all three fields have the same value.

## ✅ Expected Result
The system should display a validation message preventing users from setting the same password as their old password.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1oFATjiApbZpt4MhIrdQ2g26ZdmZCkTii/view?usp=sharing

