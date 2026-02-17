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
Bynfor rules state that sellers should not set commission higher than 60% of the listing price. Currently, the system enforces this limit for each individual level, but does not prevent the combined total of multiple levels from exceeding 60%. This allows listings to be created with total commissions exceeding the allowed maximum, which violates the documented rule and can lead to incorrect commission calculation

## 🔁 Steps to Reproduce
1. Log in to the Bynfor website as a store owner 2. Navigate to create a new listing 3. Fill in required listing details 4. Click the Commission Setup button 5. Select Level 2 and choose Percentage type 6. Set Level 1 commission to 60% and Level 2 commission to 60% 7. Click Confirm and then List Item


## ❌ Actual Result
Listing is created successfully
Total commission (120%) exceeds the allowed 60%

## ✅ Expected Result
System should prevent total commission across all levels from exceeding 60%
An error message should be displayed, e.g.: “Total commission across all levels cannot exceed 60% of the listing price”

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1y3UPrMv92fvLee-IHucLtxM8es-H5DAh/view?usp=sharing

