**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2026-01-01 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a store partnership request is rejected from a business account, the system asks for a rejection reason. However, the system accepts an invalid and meaningless input (e.g., a single digit) as a valid reason and successfully rejects the request without any validation.

## 🔁 Steps to Reproduce
1. Log in using an individual account. 2. Send a store partnership request to a business account. 3. Log in using the business account. 4. Open the received partnership request. 5. Click on Reject. 6. Enter an invalid reason such as 9. 7. Submit the rejection.


## ❌ Actual Result
The system accepts the invalid rejection reason (9) and successfully rejects the store partnership request without showing any validation error.

## ✅ Expected Result
The system should validate the rejection reason and prevent submission if the input is invalid, too short, or meaningless. A proper error message should be displayed requesting a valid reason.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1rhShl49bFAyRufVSqOJOMjXACMZmCzUs/view?usp=drive_link

