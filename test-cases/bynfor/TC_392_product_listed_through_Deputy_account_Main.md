**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-17 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a product is listed through a Deputy account, and the Main account (the account that created the deputy account) attempts to edit that product, clicking the Edit icon does not open the product editing page. Instead, the system redirects the user to the Home page, preventing the main account owner from managing listings created by their deputy.

## 🔁 Steps to Reproduce
1. Log in to Main Account (majidbusiness/Sun@Ray123) and create a Deputy user (if not already created). 2.Log in using the Deputy account (deputyuser2/Sun@Ray123) and post an item . 3.Log back in to the Main account. 4.Navigate to the listed item created by the Deputy. 4.Click the Edit icon on that product.


## ❌ Actual Result
The main account is redirected to the Home page instead of the Product Edit page.

## ✅ Expected Result
The main account should be redirected to the Product Edit page and be able to modify listings posted by its Deputy user (assuming permissions allow editing).

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1AdDChDWABtrpSOsX84aX4htvKSWo4BHQ/view?usp=drive_link

