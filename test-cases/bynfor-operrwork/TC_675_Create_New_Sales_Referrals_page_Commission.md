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
On the Create New Sales Referrals page, the Commission field has increase/decrease controls. When the decrease control is used while the value is 0, the value unexpectedly changes to 1 instead of remaining at 0.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet3) 2. Navigate to Sales Referrals 3. Click on Create New Sales Referral 4. Set Commission value to 0 5. Click on the decrease control


## ❌ Actual Result
The commission value changes from 0 to 1.

## ✅ Expected Result
The commission value should remain at 0 and should not increase when the decrease control is used.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1lMmMDvEo_8kHn86aOEdM23Bzf-uGwhaP/view?usp=sharing

