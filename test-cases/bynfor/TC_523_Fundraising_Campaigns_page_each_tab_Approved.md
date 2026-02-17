**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop/Windows 11
**Date:** 2025-11-12 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the Fundraising Campaigns page, each tab (Approved Campaigns, Rejected, History) when opened shows a count badge next to its name. After ending a campaign, the History tab updated its count but the count badge is incorrectly updated on multiple tabs, even when those tabs contain no campaigns

## 🔁 Steps to Reproduce
1. Log in to Bynfor (majidbusiness / Sun@Ray123) 2. Go to My Fundraising Campaigns page 3. Make sure you have one active campaign 4. End the campaign so it moves to History 5. Click the History tab, observe History (1) showing correctly 6. Click the Approved and Rejected tabs 7. Observe that their counts also show (1) even though no campaigns exist in those tabs


## ❌ Actual Result
The count badge updates to 1 for multiple tabs, not only the correct one. Indicates incorrect linkage between tabs

## ✅ Expected Result
Each tab should display its own independent campaign count when opened

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1ZIIslmRE6bXBglzEYlCl63gTE4VYdIjF/view?usp=sharing

