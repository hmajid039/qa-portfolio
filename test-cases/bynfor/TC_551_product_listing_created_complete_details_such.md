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
When a product listing is created with complete details such as images and return policy and then saved as Draft, the entered data is not retained. Upon reopening the draft for editing, the uploaded image is missing. Additionally, when attempting to list the item, an error is shown requesting the return policy even though it was previously provided while saving the draft

## 🔁 Steps to Reproduce
1. Open Bynfor android app (majidbusiness / Sun@Ray123) 2. Go to Seller Area → My Listing → Create Listing 3. Add product details including images and return policy 4. Save the listing as Draft 5. Open the drafted listing to edit 6. Observe the images section 7. Tap on “List Item”


## ❌ Actual Result
Uploaded product images and return policy details etc are not visible when the draft is opened for editing. On tapping “List Item”, an error message is shown even though the return policy was already added before saving the draft

## ✅ Expected Result
All entered details such as product images and return policy should be saved and retained in Draft state.
When reopening a draft listing, details should be visible and editable, and the item should be listed successfully without requesting already-provided information

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1qjVQcN-xVvQZzQ3Un21aGH4uFn4bdRHV/view?usp=sharing

