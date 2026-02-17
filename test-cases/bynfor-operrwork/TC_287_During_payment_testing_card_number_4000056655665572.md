**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-31 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
During payment testing, the card number 4000056655665572 (Visa debit test card intended to simulate a payout failure with a could_not_process code) incorrectly allows the payment to proceed successfully. This indicates that the system is not handling card failure responses correctly, leading to inaccurate test validation and potential real-world transaction issues.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log In (Account: qacomet2) 2. Navigate to the Billing & Payment Details section. 3. Enter the following test card details:  Card Number: 4000056655665572  Expiry: Any future date  CVV: Any 3 digits  4. Attempt to complete the payment.


## ❌ Actual Result
Payment proceeds successfully even though the card is expected to fail with a could_not_process error.

## ✅ Expected Result
Payment should fail and display an appropriate error message such as “Payment failed: could not process transaction”, as per the Stripe test case definition.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/14MmlS7h60SV7IEu2s3KfhH9-j-W1Vb63/view?usp=sharing

