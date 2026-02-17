**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android 15
**Date:** 2025-10-30 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
After saving a debit card (4000056655665556), clicking the Edit button for that saved card opens the edit form with the card number and CVV fields empty and with incorrect values populated in the Country and State/Province fields.

## 🔁 Steps to Reproduce


## ❌ Actual Result
upon clicking edit button for saved card, Card number and CVV fields are empty and Country and State/Province fields show incorrect values (do not match saved billing address).

## ✅ Expected Result
When opening Edit for a saved card, the form should show the card identifier (e.g., masked number like **** **** **** 1234 or last 4 digits) to let user confirm which card is being edited. CVV should not be prefilled/revealed (CVV must never be stored); however, the edit form should prompt the user to enter CVV if required for verification.The Country and State/Province fields should be prepopulated with the correct saved billing address values.

## 📎 Evidence (Screenshot/Video URI)

