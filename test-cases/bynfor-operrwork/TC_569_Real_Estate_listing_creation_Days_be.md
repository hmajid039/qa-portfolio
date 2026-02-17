**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-12-18 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In Real Estate listing creation, the “Days to be posted” field under Listing Fees → Post section specifies a maximum of 30 days, but the system allows higher values.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet3) 2. Create a Real Estate listing 3. Navigate to Listing Fees → Post section 4. Enter a value greater than 30 (e.g., 100 days) in Days to be posted 5. Submit the listing


## ❌ Actual Result
Listing is created successfully even with more than 30 days entered.

## ✅ Expected Result
System should restrict input to a maximum of 30 days and prevent listing creation with invalid values.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1OlQNI5T2J8UPuqDGAJ-vRjOIzYqzOSw7/view?usp=sharing

