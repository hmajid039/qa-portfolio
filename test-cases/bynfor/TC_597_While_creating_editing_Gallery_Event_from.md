**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-12-26 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While creating or editing a Gallery Event from the BynFor Admin panel, the system allows selecting past dates for both the event start date and end date.

## 🔁 Steps to Reproduce
1. Go to BynFor Admin panel and log in 2. Navigate to Gallery Events  3. Create a new Gallery Event 4. Select a past date for Start Date and End Date 5. Save the event 6. Edit the same event and again select past dates


## ❌ Actual Result
The system accepts previous (past) dates for event start and end dates during creation and editing.

## ✅ Expected Result
The system should restrict selection of past dates and validate that the start and end dates are current or future dates only, with proper error messages if invalid dates are selected.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1ANYrM959ydudukj_6UamNoJIe9s22J-V/view?usp=sharing

