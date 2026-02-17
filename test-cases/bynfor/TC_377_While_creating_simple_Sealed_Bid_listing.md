**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-12-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While creating a simple Sealed Bid listing, if the entered Auction reserve Price is equal to the Starting Price, the system incorrectly shows a validation error stating that the reserve must be equal to or greater than the starting price

## 🔁 Steps to Reproduce
1. Log in as a seller ((majidbusiness / Sun@Ray123)) 2. Navigate to My Listings →  Create a Listing 3. Select Sealed bid 4. Add required details for the listing 5. Enter Starting price = 500 6. Enter auction reserve = 500 7. Observe the validation error


## ❌ Actual Result
Validation error appears: “Aucion reserve must be equal to or greater than the start price.” even though both values are equal

## ✅ Expected Result
System should accept the Auction reserve price when it is equal to or greater than the Starting Price as per the rule stated

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/11OfoY47ZQcCyGpVYpC0W9dp08jIIVsmy/view?usp=sharing

