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
On the checkout page, when entering an email for PayPal payment, the system incorrectly flags all valid email addresses as invalid, displaying the message “Please enter a valid email address.” However, in some cases, Gmail addresses (e.g., user@gmail.com) are accepted without error. This inconsistency prevents most users from proceeding with PayPal payment.

## 🔁 Steps to Reproduce


## ❌ Actual Result
System shows “Please enter a valid email address.” for all valid email formats except some Gmail addresses, which are accepted.

## ✅ Expected Result
System should accept all correctly formatted and valid PayPal email addresses, regardless of domain.

## 📎 Evidence (Screenshot/Video URI)

