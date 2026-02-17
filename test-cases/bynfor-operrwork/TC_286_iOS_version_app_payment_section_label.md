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
On the iOS version of the app, the payment section label currently displays “Credit Card” when adding a new card. However, since users can also add debit cards, the label should be updated to “Credit / Debit Cards Information” for better clarity and consistency with the web version.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log In (Account: qacomet3) 2. Navigate to Billing & Payment Details. 3. Tap on Add Card under the card section. 4. Observe the title label displayed for adding a card.


## ❌ Actual Result
The section is labeled as “Credit Card”, which may mislead users into thinking debit cards are not accepted.

## ✅ Expected Result
The label should read “Credit / Debit Cards Information”, indicating both card types are supported.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/18MCkAa8nbKFfzXH1NLyFRdT2PU_7stv3/view?usp=sharing

