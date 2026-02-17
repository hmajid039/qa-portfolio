**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-11 00:00:00
**Status:** Open
**Severity:** Low
**Priority:** Medium
**Category:** UI/UX

---

## 🐞 Description
When a user unregisters a store plan, the system correctly removes the plan benefits, but the UI still displays the expiry date (e.g., “Store plan expires at 11/11”). This makes it unclear that the plan is already unregistered and no longer active.

## 🔁 Steps to Reproduce
1. Go to Bynfor and Log in(Account used: qacomet3) 2. Navigate to My Store. 3. Open the Store Plans section. 4. Unregister an active store plan. 5. Observe the plan information displayed after unregistration.


## ❌ Actual Result
The UI continues to show “Store plan expires at 11/11”, which implies the plan is still active even though the user has unregistered it.

## ✅ Expected Result
Once the plan is unregistered, the UI should clearly show “Plan Unregistered / No Active Plan” and should not suggest ongoing validity solely based on the expiry date.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1sbtVeXltCJTKgJ9LDS8XOMaAkW6Rc_es/view?usp=sharing

