**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-30 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When the user enters a correct routing number but an invalid bank account number and clicks Save, the system still displays a “Successfully added” message. This indicates missing or incorrect validation for the bank account number field, potentially allowing invalid or incomplete data to be saved.

## 🔁 Steps to Reproduce


## ❌ Actual Result
The system shows “Successfully added” even though the entered bank account number is invalid.

## ✅ Expected Result
The system should validate the bank account number before saving and display an appropriate error message such as “Please enter a valid bank account number.”

## 📎 Evidence (Screenshot/Video URI)

