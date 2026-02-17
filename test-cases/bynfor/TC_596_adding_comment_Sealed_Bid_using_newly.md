**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-12-26 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When adding comment in a Sealed Bid using a newly registered individual account without personal information, the contact number field restricts the input length after selecting country code +92 (Pakistan). However, the same contact number field in the Personal Information section correctly allows the full valid Pakistan mobile number length. This inconsistency may prevent users from entering valid contact details during the sealed bid flow

## 🔁 Steps to Reproduce
1. Register a new individual account on Bynfor 2. Do not add Personal Information 3. Navigate to Sealed Bid and attempt to add a comment 4. Select country code +92 (Pakistan) 5. Try entering a valid Pakistan mobile number 6. Observe the maximum allowed input length 7. Navigate to Personal Information section 8. Enter the same contact number and observe input behavior


## ❌ Actual Result
In the Sealed Bid comment flow, the contact number field restricts input before a valid Pakistan mobile number length is reached, while the Personal Information section allows the correct length

## ✅ Expected Result
The contact number field should enforce the same country-specific validation rules across all modules. After selecting +92, users should be able to enter a valid Pakistan mobile number length in both Personal Information and Sealed Bid comment flows

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/16yzD5jPviR23i_dHv7TLphjxzjHC2QyO/view?usp=sharing

