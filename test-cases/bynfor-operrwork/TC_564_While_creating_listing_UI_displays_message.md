**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 16-12-25
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** UI/UX

---

## 🐞 Description
While creating a listing, the UI displays message stating that the custom return policy cannot be less than 7 days. However, the system allows the seller to successfully create a listing with a custom return policy set to less than 7 days (e.g., 5 days). This results in a mismatch between the displayed rule and the actual system behavior

## 🔁 Steps to Reproduce
1. Open Bynfor android app (majidbusiness / Sun@Ray123) 2. Go to Seller Area → My Listing, click on "+" 3. Select Custom Return Policy 4. Enter return policy duration less than 7 days (e.g., 5 days) 5. Complete and submit the listing


## ❌ Actual Result
The listing is created successfully with a custom return policy of less than 7 days, despite the UI indicating that the allowed value in more than 7 and less than 365

## ✅ Expected Result
The system should enforce the stated rule and prevent listing creation when the custom return policy is set to invalid limit and text should be updated if values below 7 days are intentionally allowed

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/15lVCAL7Zr-Ww3h5YR24vZVVk_b5QDhDJ/view?usp=sharing

