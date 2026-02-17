**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-12-10 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the Tax Payer Verification page, the SSN input field allows users to enter more than the standard 9 digits, which can result in invalid or corrupt tax data.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet3) 2. Navigate to Tax Payer Verification page 3. Enter more than 9 digits in the SSN field (e.g., 123456789012)


## ❌ Actual Result
SSN field accepts more than 9 digits without any validation or error.

## ✅ Expected Result
SSN field should restrict input to exactly 9 digits and display a validation message for invalid input.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1jqUmLq9mWglHgmUmk8nmyUJmMm64VNE9/view?usp=sharing

