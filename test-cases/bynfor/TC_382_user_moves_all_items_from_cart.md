**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-13 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Payments

---

## 🐞 Description
When a user moves all items from the cart to the “Save for Later” list, the cart becomes empty, but the subtotal section remains visible showing “Subtotal: $0.00” and “Taxes: $0.00” along with an active “Continue to Checkout” button. This creates confusion as the cart visually appears to have no items but still displays checkout options.

## 🔁 Steps to Reproduce
1. Go to Bynfor app and log in (Account: qacomet3) 2. Add any product to the cart 3. Navigate to the cart page 4. Click Save for Later to move all items to the saved list 5. Observe the cart page


## ❌ Actual Result
Even after moving all items to “Save for Later,” the cart still displays:

Subtotal: $0.00
Taxes: $0.00
[Continue to Checkout] button

## ✅ Expected Result
Once all items are moved to “Save for Later,” the cart should appear completely empty and the subtotal/taxes section and checkout button should be hidden.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1mhKdKqFnTIKTXXQHhfvB8gy3ar5L0qOg/view?usp=sharing

