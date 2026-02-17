**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-13 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Functional

---

## 🐞 Description
When the user has products saved in the “Save for Later” section under the cart, removing any product works fine except for the last remaining item. Whether there was originally one or multiple products, the last item cannot be removed immediately — the system shows a success message but the product remains visible until the page is manually reloaded.

## 🔁 Steps to Reproduce
1. Go to Bynfor app and log in (Account: qacomet3) 2. Add multiple products to the cart 3. Move them to Save for Later 4. Try removing the saved items one by one 5. Observe the behavior when only one item remains in the list


## ❌ Actual Result
When removing the last product from the “Save for Later” section, the system shows a success message but the product remains visible until the page is manually reloaded

## ✅ Expected Result
;All products, including the last saved item, should be removed immediately from the “Save for Later” section once the success message appears.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1mhKdKqFnTIKTXXQHhfvB8gy3ar5L0qOg/view?usp=sharing

