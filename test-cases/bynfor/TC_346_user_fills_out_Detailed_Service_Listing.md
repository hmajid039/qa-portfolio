**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop/Windows 11
**Date:** 2025-11-07 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When the user fills out a Detailed Service Listing and attempts to save it as a draft, the system displays an incorrect and non-user-friendly error message: "Failed to save product br[object Object]". This prevents the listing from being saved and does not clearly explain the cause of the failure.

## 🔁 Steps to Reproduce
1. Go to Bynfor and log in (Account Used: qacomet3). 2. Create a new Detailed Service Listing and enter all required details. 3. Click on Save as Draft. 4. Observe the error message displayed.


## ❌ Actual Result
The system displays an unclear error message:
"Failed to save product br[object Object]"
and the draft is not saved.

## ✅ Expected Result
The listing should be successfully saved as a draft, or if an issue occurs, the system should display a clear and meaningful error message such as:
"Unable to save draft. Please try again later."
or
"Required field missing: [Field Name]"

## 📎 Evidence (Screenshot/Video URI)
https://livestore.operrwork.com/operrwork/video/2025__11/2025_11_7__17_42_12__Operr1762537332218.webm

