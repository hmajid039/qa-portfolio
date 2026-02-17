**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2026-01-05 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While creating a listing, the Relist option allows the user to enter 0 days for relisting, and the system accepts it without any validation or error message. This may lead to incorrect or unintended relisting behavior.

## 🔁 Steps to Reproduce
1. Log in to the business account (majidbusiness / Sun@Ray123) 2. Go to Create Listing 3. Enable/select the Relist option 4. Enter 0 in the “Relist after days” field 5. Submit or continue creating the listing


## ❌ Actual Result
The system accepts 0 days as a valid input and allows the listing to be created without any warning or error.

## ✅ Expected Result
The system should not allow 0 days as input for relisting. A validation message should be shown (e.g., “Relist days must be greater than 0”) or the field should restrict values to minimum 1 day.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/16iMAs3mf5EZPeib0ftCE6vHUYzAAu9Cj/view?usp=drive_link

