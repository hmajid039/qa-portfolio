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
On the Real Estate Create Listing page, the postal code field allows users to enter more than 50 digits, which exceeds valid postal code length and can lead to invalid address data.

## 🔁 Steps to Reproduce
1. Go to BynFor ios and log in (Account: qacomet3) 2. Navigate to Create Listing → Real Estate 3. Enter more than 50 digits in the Postal Code field


## ❌ Actual Result
Postal code field accepts more than 50 digits without any validation or error message.

## ✅ Expected Result
Postal code field should restrict input to a valid length and show a validation message if exceeded.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1mB2WOwSUtaoQ1nfiea8fjhlZ36pzADwn/view?usp=sharing

