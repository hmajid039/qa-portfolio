**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-26 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a user creates a business account and provides an EIN number, the system should retain that information. However, after logging in and attempting to create a seller account, the email field is auto-filled, but the EIN number is requested again. This indicates that the EIN value from the business account is not being stored or linked correctly. Moreover user can give a different EIN number in a store account.

## 🔁 Steps to Reproduce
1. Go to the registration page and create a new Business Account. 2. Enter all required details, including the EIN number. 3. Log in to the newly created business account. 4. Click on profile icon and click on  create a Seller Account. 5. Observe that while the email field is auto-filled, the EIN number field is empty and must be entered again.


## ❌ Actual Result
The system asks for the EIN number again even though it was already provided during business account creation.Also, user can provide different EIN number here.

## ✅ Expected Result
The EIN number from the business account should be automatically filled or carried over when creating a seller account.

## 📎 Evidence (Screenshot/Video URI)
https://livestore.operrwork.com/operrwork/video/2025__10/2025_10_26__15_2_37__Operr1761490956248.webm

