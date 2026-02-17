**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-28 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
For a listed offer, the tooltip indicates that the item can only be updated within 0 minutes after listing. However, the system still allows updating the item even after more than 30 minutes, which is inconsistent with the tooltip message.

## 🔁 Steps to Reproduce
1.Create and list an offer.  2.Hover over the tooltip on the listed offer to check the update restriction message.  3.Wait for more than 30 minutes after listing.  4.Try updating the item details.


## ❌ Actual Result
The item can still be updated after 30 minutes of listing.

## ✅ Expected Result
The system should prevent updates after the time mentioned in the tooltip (0 minutes) or the tooltip should display the correct allowed update duration.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1DlOaxfwzGzPcieND6mNiwerxB6aJ179I/view?usp=drive_link

