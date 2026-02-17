**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop/Windows 11
**Date:** 18-12-25
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While creating a Reverse Bid listing, the Auction Reserve field displays a tooltip that explains reserve price using normal auction logic (higher bids) which is misleading for reverse bidding, where lower bids are preferred

## 🔁 Steps to Reproduce
1. Open the Bynfor web dev(MajidB / Sun@Ray23) 2. Navigate to Create a Listing from summary 3. Select Reverse Bid as the listing type 4. Locate the Auction Reserve field 5. Click the tooltip icon next to Auction Reserve


## ❌ Actual Result
The tooltip text explains reserve price using normal auction logic, stating that bids must be “higher than the reserve price” to sell the item

## ✅ Expected Result
For Reverse Bid listings, the tooltip description should align with reverse bidding logic, explaining that lower bids are preferred or the field should be adjusted/removed if not applicable to reverse bidding

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1Om5gr2VFSVwl5KLYczQtzVpzWuJVbDjn/view?usp=sharing

