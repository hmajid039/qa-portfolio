**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-12-15 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the Create Listing page, the Postal Code field allows users to enter more than 40 digits, with no length restriction or validation applied.

## 🔁 Steps to Reproduce
1. Log in to the bynfor ios(qacomet3) 2. Navigate to Create a Listing page 3. Enter more than 40 digits in the Postal Code field


## ❌ Actual Result
Postal Code field accepts more than 40 digits without any validation error

## ✅ Expected Result
Postal Code field should restrict input to a valid length and reject excessive digits.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1t8Z2NhBhr6b--wqce_KRSctr9CMHSV6e/view?usp=sharing

