**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-04 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the web version of BynFor, a user who has listed a Sealed Bid auction is able to perform translations from the same seller account, which should not be permitted. Additionally, the system allows English-to-English translations, and these are being saved and rewarded with points — both of which are unintended behaviors. This impacts the platform’s role-based access control and point integrity system.

## 🔁 Steps to Reproduce
1. Go to BynFor web platform and log in (Account: qacomet3) 2. Create and list a Sealed Bid auction 3. From the same account, go to the translation module 4. Attempt to perform a translation (including English-to-English) 5. Save the translation and observe the points system


## ❌ Actual Result
The user is able to perform translations even after listing a Sealed Bid auction from the same account.

English-to-English translations are allowed, saved successfully, and earn points.

## ✅ Expected Result
A user who has listed a Sealed Bid auction should not be allowed to perform translations from the same account.

English-to-English translations should not be permitted or rewarded with points.

## 📎 Evidence (Screenshot/Video URI)
https://livestore.operrwork.com/operrwork/video/2025__11/2025_11_4__18_5_3__Operr1762279496929.webm

