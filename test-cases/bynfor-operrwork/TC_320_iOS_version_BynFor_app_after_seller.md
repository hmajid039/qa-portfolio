**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-11-04 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
In the iOS version of the BynFor app, after the seller fills in the auction listing details and saves it as a draft, the app incorrectly redirects to the payment options page instead of taking the user back to the drafts list. This misdirection confuses users and disrupts the expected flow for saving drafts.

## 🔁 Steps to Reproduce
1. Open the BynFor app on iOS and log in (Account: qacomet3) 2. Create a seal bid listing  3. Fill in all required listing details 4. Tap on “Save as Draft” 5. Observe the redirection behaviour after saving


## ❌ Actual Result
After saving as draft, the app redirects the user to the “Payment Options” page instead of the drafts list.

## ✅ Expected Result
After saving a listing as a draft, the user should be redirected to the “Drafts” list page where the saved draft can be viewed or edited later.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1OCUDbN4qFFh2VQlRHDgDw3jmRW4g751r/view?usp=sharing

