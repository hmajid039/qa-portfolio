**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 2025-12-31 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While creating or editing a listing in the Bynfor Android app, if a user has entered details and tries to navigate away, a warning popup (“Are you sure you want to abandon the listing?”) appears when using the bottom navigation bar. However, the warning does not appear when the user:
1. Presses the phone's Back button
2. Clicks the top-left back arrow in the app
3. Presses the phone's Home button
This can lead to accidental loss of unsaved listing data and a poor user experience

## 🔁 Steps to Reproduce
1. Open Bynfor android app (majidbusiness / Sun@Ray123)  2. Go to Seller Area → My Listing 3. Click on + to create new listing  4. Enter some listing details (e.g., title, description, images) 5. Navigate away using the bottom navigation → popup appears (verify behavior) 5. Repeat and navigate away using:    a) Phone Back button    b) Top-left back arrow    c) Phone Home button 6. Observe that the warning popup does NOT appear


## ❌ Actual Result
Warning popup appears only when using the bottom navigation

Warning popup does not appear when using back arrow, phone back button, or home button

Unsaved listing data can be lost silently

## ✅ Expected Result
The warning popup “Are you sure you want to abandon the listing?” should appear whenever the user navigates away from the listing creation page with unsaved changes, including:

Bottom navigation

Top-left back arrow

Phone Back button

Phone Home button (or at least warn before closing the app if possible)

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1fwoHo9Vjb8EYI7kyYAzlnkg0sfT3diEV/view?usp=sharing

