**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-12-10 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
When users add a product using the Instant Buy option and proceed to Checkout, the payment page opens but displays a server connection error popup, blocking payment completion.

## 🔁 Steps to Reproduce
1. Go to BynFor ios app and log in (Account: qacomet3) 2. Add any product using the Instant Buy option 3. Click on Checkout 4. Observe the payment page behavior


## ❌ Actual Result
Payment page opens but an error popup appears displaying: “URL sessionTask failed, couldn't connect to server”.

## ✅ Expected Result
Payment page should load successfully and allow users to complete the payment without any server connection errors.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/14TbvQ8LSXQLKWTAmQdmXpcdlqsoPXb-q/view?usp=sharing

