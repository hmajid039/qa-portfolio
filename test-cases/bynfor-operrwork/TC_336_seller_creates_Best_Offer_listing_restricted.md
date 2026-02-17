**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-06 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a seller creates a Best Offer listing restricted to a specific region (e.g., Madhya Pradesh, India), buyers whose shipping addresses fall within the allowed region are incorrectly prevented from adding the product to the cart. The system displays an error: “Seller is not selling in your region,” even though the buyer’s address matches the seller’s allowed region. This impacts the purchasing process and could lead to loss of sales for sellers targeting specific regions.

## 🔁 Steps to Reproduce
1. Open BynFor with seller account (Account used: qacomet3). 2. Create a Best Offer listing restricted to a specific region (e.g., Madhya Pradesh, India). 3. Open the buyer account (Account used: Nikitatesteraccount). 4. Ensure buyer account shipping address is in the same region (Madhya Pradesh). 5. Buyer tries to add the product to the cart.


## ❌ Actual Result
Buyer sees an error stating “Seller is not selling in your region,” even though the shipping address is within the allowed region.

## ✅ Expected Result
Buyer should be able to add the product to the cart without any region restriction errors, as the shipping address matches the seller’s allowed region.

## 📎 Evidence (Screenshot/Video URI)
https://livestore.operrwork.com/operrwork/video/2025__11/2025_11_6__17_21_13__Operr1762449661820.webm

