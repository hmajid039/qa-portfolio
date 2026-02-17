**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-12-31 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the Become a Partner page, when the Country field is auto-filled from the user profile with a country other than USA, the State field does not load the corresponding state dropdown. The state dropdown appears only after the user manually re-selects the same country from the country dropdown.

## 🔁 Steps to Reproduce
1. Go to BynFor dev and log in (Account: qacomet3) 2. Ensure the profile country is set to a country other than USA 3. Navigate to the Become a Partner page 4. Observe the State field behavior 5. Re-select the same country from the Country dropdown


## ❌ Actual Result
State dropdown is not populated when country is auto-filled; it appears only after re-selecting the country manually.

## ✅ Expected Result
State dropdown should automatically load and display relevant states based on the auto-filled country.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1gYUHXVZ0lNfveM9b3dSFuTCgKzIef7uh/view?usp=sharing

