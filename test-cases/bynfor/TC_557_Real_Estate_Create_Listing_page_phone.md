**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-12-16 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the Real Estate Create Listing page, the phone number field allows users to enter even a 1-digit phone number, resulting in invalid contact information being saved.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet3) 2. Navigate to Create Listing → Real Estate 3. Enter only 1 digit in the Phone Number field 4. Save or proceed with the listing


## ❌ Actual Result
Listing is accepted with a 1-digit phone number without any validation error.

## ✅ Expected Result
Phone number field should enforce a minimum valid length and show a validation error for incomplete numbers.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1xnKSdv1YiVBUoD0us1IoSpNjgY4bvsZJ/view?usp=sharing

