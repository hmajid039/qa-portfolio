**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-26 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
On the Bank Details page, the Bank Account Number field does not display any error when a user enters fewer digits than the mandatory requirement. This allows users to submit incomplete bank account numbers, which may cause payment failures or account setup issues.

## 🔁 Steps to Reproduce
1. Go to BynFor and log in as a seller (Individual or Business account). 2. Go to Music lcategory listing page                                3. Fill all details and clcik on list 4. Click on Bank account radio botton 5. Enter a bank account number with fewer digits than the required minimum. 6. Click Save.


## ❌ Actual Result
The system allows saving the bank account number without showing any error message, even though it does not meet the mandatory length requirement.

## ✅ Expected Result
The system should validate the bank account number length and display an error message if the entered number is shorter than the mandatory requirement.

## 📎 Evidence (Screenshot/Video URI)
https://livestore.operrwork.com/operrwork/video/2025__10/2025_10_26__17_57_0__Operr1761501388840.webm

