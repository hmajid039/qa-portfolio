**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-30 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Security

---

## 🐞 Description
After saving bank details, the system shows a success message. However, when reopening the same section to edit, sensitive fields such as Bank Account Number, CVV, and Card Address appear entirely blank. No masked values (e.g., ****1234) or placeholder text (e.g., “Hidden for security”) are shown.

## 🔁 Steps to Reproduce


## ❌ Actual Result
After saving, the bank detail fields show no values — not even masked or hidden placeholders — when reopened in edit mode.

## ✅ Expected Result
Saved sensitive fields should either display masked values (e.g., ****1234) or show a placeholder like “Hidden for security” to indicate that data was stored securely.

## 📎 Evidence (Screenshot/Video URI)

