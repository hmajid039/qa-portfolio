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
In the Monetary Gift module, the per-person gift amount is calculated incorrectly when a total price and number of people are provided.

## 🔁 Steps to Reproduce
1,. Go to BynFor app and log in (Account: qacomet3) 2. Navigate to Monetary Gift section 3. Set Total Price = $4.00 4. Set People = 10 5. Observe the per-person gift amount displayed


## ❌ Actual Result
Each person is shown to receive $0.25.

## ✅ Expected Result
Each person should receive $0.40 ($4.00 ÷ 10 people).

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1OmH12k-8OzJc2uD9uscoH4z8jIWe6KOx/view?usp=sharing

