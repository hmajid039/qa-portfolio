**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-12-29 00:00:00
**Status:** Open
**Severity:** Low
**Priority:** Medium
**Category:** UI/UX

---

## 🐞 Description
While rejecting a distributor request, the rejection reason field is marked as required. However, the system allows the user to enter only blank spaces and still successfully submit the rejection. This allows rejection without a valid reason, which should not be permitted

## 🔁 Steps to Reproduce
1. Log in to the Bynfor dev website(majidbusiness / Sun@Ray123) 2. Click on the avatar located in the top right corner 3. Navigate to Partnerrship programs -> Distributor Partnership -> Review Distributor Level 1 4. Click on View -> click Reject 5. In the rejection reason field, enter only spaces 6. Click on okay button 7. Observe the result


## ❌ Actual Result
The system accepts spaces-only input in the rejection reason field and completes the rejection successfully

## ✅ Expected Result
The system should not accept spaces-only input. An error message should be shown asking the user to enter a valid rejection reason before proceeding

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1alGl9EfXvVxzKluuS1Fiwn6spxIZuAvp/view?usp=sharing

