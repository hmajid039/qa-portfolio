**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-01-06 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the iOS BynFor app, the Commission field on the New Sales Commission creation page allows entering a value of 0, whereas the same value is not allowed in Dev BynFor (web). This causes inconsistent validation across platforms.

## 🔁 Steps to Reproduce
1. Log in to the BynFor iOS app(qacomet1) 2. Navigate to Sales Referrals →Sales referrals Commission 3. Tap on Create New Commission 4. Enter 0 in the Commission field 5. Attempt to save


## ❌ Actual Result
The system accepts 0 as a valid commission value on iOS.

## ✅ Expected Result
The Commission field should not accept 0, consistent with validation rules in Dev BynFor.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1GXJ8RKi3qx40HVMfUh_JBXXpz_PvYpew/view?usp=sharing

