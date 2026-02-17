**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-07 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While creating a Detailed Service Listing, the Postal Code field allows the user to enter alphabetic characters and special characters. No validation or error message is displayed. This may lead to incorrect or invalid listing location data.

## 🔁 Steps to Reproduce
1. Go to Bynfor and log in (Account Used: qacomet3). 2. Create a new Detailed Service Listing. 3. In the Postal Code field, enter letters (e.g., "ABCD") or alphanumeric values (e.g., "12AB3"). 4. Proceed to the next step or save the listing.


## ❌ Actual Result
The Postal Code field accepts alphabetic or non-numeric characters without any validation error.

## ✅ Expected Result
The Postal Code field should accept only numeric values and should show a validation error when characters are entered.

## 📎 Evidence (Screenshot/Video URI)
https://livestore.operrwork.com/operrwork/video/2025__11/2025_11_7__17_32_57__Operr1762536773613.webm

