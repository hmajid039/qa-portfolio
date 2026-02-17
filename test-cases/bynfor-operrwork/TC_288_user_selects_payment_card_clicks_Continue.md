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
When a user selects a payment card and clicks Continue to proceed with checkout, the system incorrectly displays the message “Select payment mode” on the first attempt. The issue does not occur on retry, indicating a delay or failure in capturing the selected payment mode during the initial attempt.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log In (Account: qacomet3) 2. Add any product to the cart and proceed to the Checkout page. 3. Navigate to the Payment Section. 4. Select a valid card payment option. 5. Click Continue to proceed with checkout.


## ❌ Actual Result
On the first attempt, the message “Select payment mode” appears even though a valid card is selected. On the second attempt, the checkout proceeds successfully.

## ✅ Expected Result
The checkout process should proceed successfully on the first attempt once a valid payment card is selected, without showing any error message.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/14MmlS7h60SV7IEu2s3KfhH9-j-W1Vb63/view?usp=sharing

