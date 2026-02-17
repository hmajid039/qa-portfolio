**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 16-12-25
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the Active Listing tab, for newly created listings an info icon appears with text similar to: “You can only revoke and update the listing the item within 30 minutes after listing. Are you sure you have the item and as what you described?” However: For listings that were created more than 30 minutes ago, this info message is not shown, but the edit and delete icons are still active and functional.
After editing such an older listing and tapping List Item, the listing is updated and the same 30‑minute info message appears again, even though more than 30 minutes have already passed since the original listing time.
This behavior is confusing and seems to contradict the message about “only within 30 minutes”

## 🔁 Steps to Reproduce
1. Open the Bynfor Android app ( majidbusiness / Sun@Ray123) 2. Go to Seller Area → My Listing → Create Listing 3. Fill in all required details and tap List Item 4. Go to the Active tab and locate the newly created listing 5. Observe the info icon and its message (about only being able to revoke/update within 30 minutes). 6. Wait more than 30 minutes 7. Tap Edit on this listing (more than 30 minutes old) 8. Then click on list item is visible and observe


## ❌ Actual Result
For listings older than 30 minutes, the info message about the 30‑minute limit is not visible, but the Edit and Delete/Revoke icons are still active and work. After editing the "list item" button is there, as if new listing is being created

## ✅ Expected Result
If the rule is “You can only revoke/update within 30 minutes”: After 30 minutes Edit and Delete actions should be disabled or blocked. If editing and revoking are allowed any time: The current 30‑minute warning text is misleading and should match the real behavior

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/129xbtMomcgX7aa8abMGYjINwMD80ifz8/view?usp=sharing

