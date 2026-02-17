**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-29 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While creating a best offer listing, when the user enters a Listing Price (e.g., $900) and then sets the Minimum Price (Reserve Price) to a lower value (e.g., $850), the system shows an error message stating that the reserve price “should be 900 or more.” This is incorrect, as the reserve price should always be less than or equal to the listing price.

## 🔁 Steps to Reproduce


## ❌ Actual Result
The system shows an error: “Minimum Price should be 900 or more,” preventing valid input.

## ✅ Expected Result
The Minimum Price (Reserve Price) should allow values less than or equal to the listing price and show an error only when it exceeds the listing price.

## 📎 Evidence (Screenshot/Video URI)

