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
A sales referral entry is created when the buyer is the same user (or same account) as the referrer/seller. Sales Referrals should only be generated for third-party purchases, not self-purchases.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet3) 2. Purchase a product listed by the same user or via own referral 3. Navigate to Sales Referrals 4. Open the referral entry details


## ❌ Actual Result
A Sales Referral entry is shown where Buyer = logged-in user, with status Ordered and commission $0.00.

## ✅ Expected Result
No Sales Referral entry should be created for self-purchases; such orders should only appear in order history/seller sales.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1sjfZ1aTpFjVYYyQz3xQJJ5oxzvCSl_r4/view?usp=sharing

