**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 16-12-25
**Status:** Open
**Severity:** Low
**Priority:** Medium
**Category:** UI/UX

---

## 🐞 Description
After creating an active product listing with all required details (including return policy and shipping details), editing the listing and changing only the quantity results in validation errors.
The app shows “Please provide return policy” and requires the user to enter shipping details again, even though both were already provided when the product was first liste

## 🔁 Steps to Reproduce
1. Open Bynfor Android app (majidbusiness / Sun@Ray123) 2. Go to Seller Area → My Listing → Create Listing 3. Fill in all required product details, including Return Policy 4. Tap List Item so the product is successfully created and appears under Active Listings 5. Open the same active listing and tap Edit 6. Change only the Quantity field; do not touch the return policy or other required fields 7. Tap List Item


## ❌ Actual Result
On tapping List Item, the app shows an error: “Please provide return policy”. Shipping details that were previously provided are also not retained; the app requires the user to re‑enter / re‑select shipping details again. The update cannot be completed unless return policy and shipping details are re‑filled, even though they were already provided when the listing was created

## ✅ Expected Result
Previously provided return policy and shipping details should be retained when editing an active listing and the user should be able to change only the quantity and successfully tap List Item without being asked again for return policy or shipping information

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1QwKhGe_ohNLz6LaQMXv-iwFp3jIYG7Os/view?usp=sharing

