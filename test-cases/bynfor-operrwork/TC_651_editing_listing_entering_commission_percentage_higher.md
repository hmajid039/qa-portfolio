**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-12-31 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When editing a listing, entering a commission percentage higher than 60% correctly shows a validation error under the field. However, clicking the Update button still saves the listing successfully with the invalid value. This allows commission percentages above the allowed limit and indicates that validation is not enforced on submission

## 🔁 Steps to Reproduce
1. Log in to the Bynfor website as a store owner 2. Create a listing with Level 1 commission set to 60% (valid) 3. Open the listing and click Edit 4. Change the commission percentage to >60 5. Observe the validation error shown under the field 6. Click Update / Save


## ❌ Actual Result
Validation error is displayed under the commission field

Listing updates successfully

Commission percentage is saved as > 60

## ✅ Expected Result
Update action should be blocked when validation error is present

Commission percentage above 60% should not be saved

A clear error message should prevent submission

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1pL5QxaauNNIHuVTrHQo5_T7eh31r1VVt/view?usp=sharing

