**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 15-12-25
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
A product listing saved as Draft shows a Delete icon in the My Listing → Drafts tab. However, when the Delete icon is tapped, the confirmation popup says: "are you sure that you want to withdraw this listing?", and on confirmation the system shows: "only active products can be withdrawn"

## 🔁 Steps to Reproduce
1. Open Bynfor Android app (majidbusiness / Sun@Ray123) 2. Go to Seller Area → My Listing → Drafts 3. Open any drafted listing 4. Tap on the Delete icon 5. Confirm by tapping “Yes” on the popup


## ❌ Actual Result
A popup appears saying “Are you sure you want to withdraw this listing?”
After confirmation, an error message is shown:
“Only active products can be withdrawn”
The draft listing is not deleted

## ✅ Expected Result
Draft listings should be deleted, not withdrawn
Either: The Delete icon should successfully delete the draft or the Delete icon should not be shown if the action is not supported

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1LMlaMxxZCe-Dch-7HiiOCmI9wyHg1tUh/view?usp=sharing

