**Reported By:** Majid Ali
**Environment:** Staging
**Device:** android 15
**Date:** 2025-10-12 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a user adds a product from Instant Buy to the cart and sets a quantity (e.g., 4), using the “-” button to lower the quantity works. However, clicking the “+” button to increase the quantity again shows the message “Maximum order quantity reached”, even though the user has not reached any defined product limit

## 🔁 Steps to Reproduce
1. Open the Bynfor app android(appuser / Sun@Ray123) 2. Navigate to Marketplace -> Instant Buy 3. Add a product to the cart with quantity 4 4. Open the cart 5. Click the “-” button to decrease the quantity, it works 6. Click the “+” button to increase the quantity, observe error message “Maximum order quantity reached”


## ❌ Actual Result
Quantity decreases with “-” button, quantity cannot be increased again; error message displayed incorrectly

## ✅ Expected Result
Quantity should increase correctly up to the allowed product maximum. The “Maximum order quantity reached” message should only appear when the actual maximum product limit is reached

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1bItSCE0VaffKjTFT2OJwDZ9cte-hYznT/view?usp=sharing

