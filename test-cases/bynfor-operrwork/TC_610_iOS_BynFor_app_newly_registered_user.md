**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-12-29 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the iOS BynFor app, a newly registered user attempting to create a store sees a “View Your Store” button even though no store has been created. Clicking this button redirects the user to a different (existing) store, causing confusion and potential data exposure.

## 🔁 Steps to Reproduce
1. Open BynFor iOS app 2. Register/login with a new user account 3. Navigate to Create Store section 4. Observe the “View Your Store” button and tap on it


## ❌ Actual Result
“View Your Store” button is shown for a new user and redirects to another user’s store.

## ✅ Expected Result
New users without any store should not see the “View Your Store” button. They should only see options to create a new store, and no redirection to other stores should occur.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1umSBUtGzZXw73McphU9x5GfrJCtA3GE7/view?usp=sharing

