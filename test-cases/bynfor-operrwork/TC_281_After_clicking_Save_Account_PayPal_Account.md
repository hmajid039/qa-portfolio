**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-31 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
After clicking Save Account on the PayPal Account page, a confirmation popup appears with incorrect text (address-related). Clicking Cancel on that popup unexpectedly still saves the PayPal account instead of aborting the action.

## 🔁 Steps to Reproduce
1. Login to Bynfor wesite (majidbusiness/Sun@Ray123). 2. Go to payment details page.   3.Enter valid PayPal account details. 4.Click Save Account. 5.When the confirmation popup appears, click Cancel. 6.Verify whether the account was saved.


## ❌ Actual Result
Clicking Cancel on the confirmation popup still saves the PayPal account. The confirmation popup text is also incorrect (references address instead of PayPal account).

## ✅ Expected Result
Clicking Cancel should abort the save action and not save the PayPal account.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/107h59MMXuJ0WO8dWxzgfP0AvYZyB5Z09/view?usp=drive_link

