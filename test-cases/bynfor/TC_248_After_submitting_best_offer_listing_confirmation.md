**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-29 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
After submitting a best offer listing, the confirmation popup displays “You can revoke or update listing within 0 minutes.” The value is incorrect (zero) and misleads sellers about their ability to modify the listing. The popup should show the actual configured time window (a positive integer) instead of 0.

## 🔁 Steps to Reproduce


## ❌ Actual Result
Popup text reads: “You can revoke or update listing within 0 minutes.”

## ✅ Expected Result
Popup should display the actual configured non-zero time window (for example: “You can revoke or update listing within 10 minutes”) or a clearly worded statement if edits are not allowed (e.g., “This listing cannot be revoked or updated after submission”).

## 📎 Evidence (Screenshot/Video URI)

