**Reported By:** Majid Ali
**Environment:** Staging
**Device:** android 15
**Date:** 2025-10-12 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a user purchases a 1-month(Price: 101.0) Real Estate Membership, the membership status shows inconsistent values:
Real Estate Listings Limit: Unlimited (should be 10 according to package rules)
Times Left: 10

## 🔁 Steps to Reproduce
1. Open the Bynfor app android(appuser / Sun@Ray123) 2. Go to Summary -> Membership 3. Navigate to Real Estate Membership tab 4. Tap on Register for monthly membership (price: 101.0) 5. Observe the data shown on the membership status section after


## ❌ Actual Result
Incorrect data: Real Estate Listings Limit: Unlimited
Listings Left: 10

## ✅ Expected Result
Correct data as per purchased package: Real Estate Listings Limit: 10 (as per package rules)
Times Left: Correct remaining listings according to purchased package

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1B-nfkkksq0qAzLp7UdpmclVwt-TTW4wK/view?usp=sharing

