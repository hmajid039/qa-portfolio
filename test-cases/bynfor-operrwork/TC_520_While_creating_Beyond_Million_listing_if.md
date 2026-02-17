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
While creating a Beyond Million listing, if the seller enters only the start date and end date but leaves the duration field empty, the system auto-sets the duration to 3, even though the actual date range spans many days.

## 🔁 Steps to Reproduce
1. Go to BynFor and log in (Account: qacomet3) 2. Create a Beyond Million Listing 3. Select a start date and an end date with a long gap (e.g., 20+ days) 4. Do not enter anything in the Duration field 5. Save or proceed


## ❌ Actual Result
Duration field automatically populates with 3, which does not match the selected date range.

## ✅ Expected Result
System should auto-calculate the correct duration based on the start and end dates, or should not set any duration unless the user enters it manually.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/19F2URWVne78BHmrOceLtXBtsyABaNmiI/view?usp=sharing

