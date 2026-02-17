**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-05-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Payments

---

## 🐞 Description
When we use card number(4000056755665555        tok_visa_debit_us_instantPayoutUnsupported        Visa debit. Card isn’t eligible for Instant Payouts.) during checkout to place order, the card is added successfully and order placement also succeeds

## 🔁 Steps to Reproduce
1. Go to bynfor website (credentials: user888, user123 ) 2. Click on instant buy 3. Choose any product and click on buy now 4. Add card: 4000056755665555 5. Add required details and address details 6. Save card and observe that the order is placed successfully


## ❌ Actual Result
Order placement was successful — payment was accepted, and the order appeared in the “Purchases” section, even though the card type indicates it should not support Instant Payouts.

## ✅ Expected Result
The system should reject the payment with a message like “Card not eligible for Instant Payouts" using backend logic

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1kdzNNfkwo48oZ4Far0Y4aREaYqPs2Mo-/view?usp=sharing

