**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-13 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a user tries to add a product to the cart with a quantity higher than the available stock, the system displays an incorrect error message showing a placeholder variable ({{productName}}) instead of the actual product name. This creates confusion and makes the message look unprofessional.

## 🔁 Steps to Reproduce
1. Go to Bynfor app and log in (Account: qacomet3) 2. Go to any product detail page 3. Enter a quantity greater than the available stock (e.g., 55 when stock is 50) 4. Click on Add to Cart


## ❌ Actual Result
System shows an incorrect message with a placeholder instead of the product name:

“The maximum available quantity of "{{productName}}" is 50.”

## ✅ Expected Result
System should display a clear and user-friendly message with the product name, such as:

“You can only add up to 50 units of Earings.”

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1EB-b3aWeiwHpubg0UnQzLWZUWGcYLvlS/view?usp=sharing

