**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 16-12-25
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the Drafts tab of My Listing, the listing type filter displays inconsistent behavior. When filtering by Service type, the relevant draft listing is shown correctly. However, when filtering by Sale type, the application shows “You don't have listing” even though a Sale-type draft listing exists and is visible under the All filter and maybe due to issue in draft listing filter logic

## 🔁 Steps to Reproduce
1. Open Bynfor android app (majidbusiness / Sun@Ray123) 2. Go to Seller Area → My Listing → Drafts 3. There are at least two draft listings 4. Select “All” from the filter dropdown and confirm both drafts are visible 5. Select “Service” from the filter dropdown 6. Select “Sale” from the filter dropdown


## ❌ Actual Result
Service-type draft listing is displayed correctly when the Service filter is applied, Sale-type draft listing is not displayed and the screen shows “You don't have listing”

## ✅ Expected Result
Draft listings should be displayed correctly based on the selected listing type. Draft listings should appear when their respective filters are applied, provided such drafts exist

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/12kgGaaM_PXn6jQmGJK96GS8CRo6BVBQK/view?usp=sharing

