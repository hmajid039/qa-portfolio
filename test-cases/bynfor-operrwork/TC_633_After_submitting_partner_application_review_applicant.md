**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-12-30 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
After submitting a partner application for review, the applicant is still able to click Edit and Save as Draft. This effectively withdraws the application from the store’s review queue without any warning. Allowing edits or reverting to draft while the application is under review is not expected behavior and can confuse both the applicant and the store and disrupt the review process

## 🔁 Steps to Reproduce
1. Log in to the Bynfor dev (Account A) 2. Navigate to Partnership Programs → Become Store Partner / Distributor 3. Fill all required fields and click Submit for Review 4. Observe status changes to Pending 5. Click Edit and make changes to the application 6. Click Save as Draft 7. Observe status changes to Draft and application disappears from store review queue


## ❌ Actual Result
1. Edit button remains active after submission
2. Clicking Save as Draft changes status from Pending → Draft
3. No warning or confirmation is shown
4. The application is removed from the store’s review list

## ✅ Expected Result
1. Once submitted, the application should not be editable until rejected or withdrawn explicitly
2. Save as Draft option should be disabled after submission
3. If editing or reverting is allowed, a clear warning should indicate that it will cancel or resubmit the review

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1GsaERUtfpODU4W1FK6UzrRl7i3KDD5F_/view?usp=sharing

