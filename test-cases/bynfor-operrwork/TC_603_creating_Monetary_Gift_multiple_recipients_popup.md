**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-12-26 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When creating a Monetary Gift for multiple recipients, the popup displays a minimum amount based on the formula:
Minimum amount you can share = Quantity × $0.01. But entering an amount equal to this displayed minimum (e.g., $0.03 for 3 recipients) triggers a validation error. This is contradictory with the displayed rule and may confuse users, the displayed rule should be updated so that users can enter the correct amount

## 🔁 Steps to Reproduce
1. Login as User A( majidbusiness / Sun@Ray123 ) 2. Navigate to social media -> moments 3. Share a Monetary Gift on wall In the popup: Select Max people can claim = 3 Observe displayed minimum: $0.03 Enter Amount = 0.03 → Submit


## ❌ Actual Result
Form displays a validation error and does not allow submission

## ✅ Expected Result
Form should allow submission for the minimum amount being shown by the system or the displayed rule should reflect the correct minimum value, so users do not encounter unexpected errors

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1ts6m_hQaCUgZeR9_RaC9irOTJLGE6f_K/view?usp=sharing

