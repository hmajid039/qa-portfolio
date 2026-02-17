**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
After purchasing a membership, the system immediately displays 364 days left instead of the expected 365. This happens because the system likely calculates the date difference using full 24-hour intervals which excludes the current day’s partial hours This can confuse users, as they expect to see a full 365 days right after buying a 1-year membership or a monthly membership

## 🔁 Steps to Reproduce
1. Log in to the bynfor website(majidbusiness, Sun@Ray123) 2. Go to My Account → Membership 3. Purchase a membership (e.g., Platinum) 4. After purchase, check the membership details 5. Observe the “Days Left” value


## ❌ Actual Result
The display "Days left" shows one day less than the total duration immediately after purchase

## ✅ Expected Result
“Days Left” should display 365 or 30 immediately after purchase to represent the full duration avoiding confusion for end users

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1bYd39U02sWQOkMcYQ-JDUgu5BxUCHehA/view?usp=sharing

