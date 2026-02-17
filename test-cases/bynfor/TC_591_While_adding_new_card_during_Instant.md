**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-12-24 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
While adding a new card during the Instant Buy payment flow, the CVV field initially shows a validation error when left empty. However, after filling other required card fields, the CVV validation indicator (red underline) disappears even though the CVV field is still empty. At the same time, the Save Card button remains disabled without any message

## 🔁 Steps to Reproduce
1. Login to Bynfor QA 2. Navigate to Instant Buy checkout 3. Select Add New Card 4. Leave the CVV field empty 5. Fill in other required fields (Card Number, Expiry Date) 6. Observe the CVV field validation state and Save Card button


## ❌ Actual Result
The CVV field validation indicator (red underline) disappears even though the field is empty, while the Save Card button remains disabled without any indication of the missing required field.

## ✅ Expected Result
If CVV is required and not filled: CVV field should continue to show validation error (red underline / message), or
Clear message should indicate CVV is required
Save Card button should remain disabled with clear indication of missing required field

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1FeN7mTgdUOXUwb4ejMW2f2ZeFHyWumC4/view?usp=sharing

