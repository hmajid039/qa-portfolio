**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-12-30 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
After a Level 1 distributor pays the nominal verification fee (shown in transaction history) and a sale occurs through their distributor link, the wallet shows the reward as “Upcoming,” but the tooltip incorrectly states that the fee has not been paid. This is misleading and can confuse the user about the payment

## 🔁 Steps to Reproduce
1. Log in to the Bynfor dev website as Account A 2. Submit and get approved for a partner application for Account B’s store 3. Pay the nominal verification fee as Account A(Transaction shows in history) 4. Log in as Account B and list a product with commission enabled 5. Account A shares the product link with Account C 6. Account C buys the product 7. Log in as Account A and check wallet and hover over the “i” icon for the reward


## ❌ Actual Result
Tooltip incorrectly says the nominal verification fee has not been paid for the Upcoming reward of commission

## ✅ Expected Result
Tooltip should correctly reflect that the nominal verification fee paid status for the upcoming reward

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/16VMIWIA-dot8M1j8B7VfTVmj8tJWKO7G/view?usp=sharing

