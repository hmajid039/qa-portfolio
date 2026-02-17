**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-30 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
When the user enters details of a closed or inactive bank account and clicks Save, the system still displays a “Successfully added” message. This indicates missing validation for verifying the account’s active status, which could lead to payment failures or invalid data being stored.

## 🔁 Steps to Reproduce


## ❌ Actual Result
The system accepts a closed bank account and confirms it as successfully added.

## ✅ Expected Result
The system should validate the account status and display an appropriate error message such as “This bank account is closed or inactive.”

## 📎 Evidence (Screenshot/Video URI)

