**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop/Windows 11
**Date:** 2025-12-24 00:00:00
**Status:** Open
**Severity:** Low
**Priority:** Medium
**Category:** UI/UX

---

## 🐞 Description
While creating a Gallery Event from admin side, the Name field is marked as required. However, when only spaces are entered in the Name field, the system still allows
the event to be created successfully. This leads to invalid event data and indicates required-field validation

## 🔁 Steps to Reproduce
1. Login as Admin admin.bynfor.com 2. Navigate to Fine Arts Gallery Event 3. Click on + to add event 4. In Name* field, enter only spaces (e.g. " ") 5. Fill all other required fields with valid data 6. Click Create Event


## ❌ Actual Result
Event is created successfully even though the Name field contains only spaces

## ✅ Expected Result
System should trim spaces and treat the Name field as empty.
Validation error should be shown for required field. Event should not be created

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/13Wh1ObiqxVVW6UwWrl3Sebxjl3HF6Vef/view?usp=sharing

