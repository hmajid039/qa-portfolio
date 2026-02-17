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
While entering a fixed commission amount for a commission level, the system displays an error message stating “The total amount should not be more than $12000”. However, this message is shown even when the value entered in the field is exactly $12,000. The validation message is contradictory and unclear, as it refers to a “total amount” while validating a single field and does not clearly indicate the actual allowed value

## 🔁 Steps to Reproduce
1. Log in as a store owner 2. Create a listing with price $20,000 3. Open Commission Setup 4. Select Level (2 or 3) 5. Choose Fixed commission type 6. Enter $12,000 in each amount field separately 7. Observe the validation message


## ❌ Actual Result
Error message is displayed:
“The total amount should not be more than $12000”

Error appears even though the entered value equals $12,000

## ✅ Expected Result
The system should validate commission amounts using clear and consistent rules.
If an allowed value for the field is selected, no validation error should be shown

If value added is not allowed, the system should:
Clearly state the actual maximum allowed commission for that field
and
Use field-specific wording instead of “total amount”

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1SRusm3oiB2gTdWqzs8RXCOPYPUcyoAv5/view?usp=sharing

