**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-28 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the iOS app Listing Product page, when the user selects the same  end date for a listing, the app automatically changes the end date to the next day after saving. Additionally, the expected validation message — “Listing end date must be after the current time.” — is missing. This leads to confusion and incorrect listing scheduling behavior.

## 🔁 Steps to Reproduce
1. Open the iOS app. 2. Navigate to the Listing Product page. 3. Select the same date for Listing End Date in the calendar. 4. Tap Save. 5. Observe the behavior in the date field after saving.


## ❌ Actual Result
The app automatically changes the end date to the next day without user confirmation.

The expected validation message “Listing end date must be after the current time.” is not displayed.

## ✅ Expected Result
The system should not automatically modify the user’s selected date.

When the user selects the  end date same as start date, a validation error message — “Listing end date must be after the current time.” — should appear to guide the user.

The user should manually select a valid end date after being notified of the error.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1Bo-GUrRbt7SQHCf226AL4AoGQxbQiKQp/view?usp=sharing

