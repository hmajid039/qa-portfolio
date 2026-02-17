**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 16-12-25
**Status:** Open
**Severity:** Low
**Priority:** Medium
**Category:** UI/UX

---

## 🐞 Description
In the Active tab of My Listing, each listing displays its package information such as “Annual Package”, “Membership Package”, or “30 Day Trial”. However, when filters are applied (for example, changing the listing type from All to Sale or Real Estate), the package information displayed for the same listing changes inconsistently and may revert or change again when filters are reapplied. This indicates incorrect data binding or UI refresh logic during filter operations

## 🔁 Steps to Reproduce
1. Open Bynfor android app (majidbusiness / Sun@Ray123) 2. Go to Seller Area → My Listing → Active 3. Observe the package information shown on listings 4. Apply a filter (e.g., change listing type from All to Sale or Real Estate) 5. Observe the package information on the same listing 6. Change the filter again or reset it


## ❌ Actual Result
The package information (e.g., Annual Package, Membership Package, 30 Day Trial) displayed for a listing changes unexpectedly when filters are applied or changed, even though the listing itself remains the same

## ✅ Expected Result
Package information for a listing should remain consistent and unchanged regardless of filter application.
Applying or changing filters should only affect which listings are displayed, not alter the package or membership details of existing listings

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1Y8I-U2Bnk3J17u4YyUJG0BEsfKY-eSax/view?usp=sharing

