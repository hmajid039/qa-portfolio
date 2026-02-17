**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-04-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When testing Visa debit card 4000056655665572 (expected payout failure with "could_not_process"), the system allows the order to complete successfully, the card is added and lists it under “My Purchases.”

## 🔁 Steps to Reproduce
1. Go to bynfor website (credentials: user888, user123 ) 2. Click on instant buy 3. Choose any product and click on buy now 4. Add credit/debit card 5. Add required details and address details 6. Save card and observe that the order is placed successfully


## ❌ Actual Result
Order is placed successfully using test card configured to fail (4000056655665572        tok_visa_debit_us_transferFail        Visa debit. Payout fails with a could_not_process code.)

## ✅ Expected Result
User should see an error: “Payment could not be processed.” or  Order should not be created

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1VqjXKnq5I-mac9D5SaUnYovQ8xgVjFXL/view?usp=sharing

