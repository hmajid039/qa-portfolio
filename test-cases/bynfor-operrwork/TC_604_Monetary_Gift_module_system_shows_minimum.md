**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-12-28 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the Monetary Gift module, the system shows a minimum amount validation error even when the entered total amount is higher than the calculated minimum based on quantity.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet3) 2. Navigate to Monetary Gift 3. Enter Quantity = 200 people 4. Verify calculation applied: 200 × $0.01 = $2.00 5. Enter Total Amount = $3.00 6. Observe the validation message


## ❌ Actual Result
Error displayed:

"Based on the calculation, the lowest amount is less than 0.01 USD, please increase your total amount or reduce the quantity."

## ✅ Expected Result
No error should be shown since $3.00 ≥ $2.00, which satisfies the minimum amount requirement.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1LR8wI7ZSxlxTN14yD39zHWt6CiGx96zU/view?usp=sharing

