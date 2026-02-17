**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 2025-12-31 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Security

---

## 🐞 Description
While setting up commission for multiple levels in the Bynfor Android app, the keyboard type behaves inconsistently: Clicking on the Level 1 commission field opens a numeric keyboard (numbers only)
Clicking on Level 2 or Level 3 fields opens the normal alphanumeric keyboard

This can confuse users and can lead to input errors when entering commission amounts. All numeric commission fields should consistently open the numeric keyboard

## 🔁 Steps to Reproduce
1. Open Bynfor Android app (majidbusiness / Sun@Ray123) 2. Go to Seller Area → My Listing 3. Click on + to create a new listing 4. Enter listing details and click on Commission Setup 5. Select multiple levels (Level 1, Level 2, Level 3) 6. Click on Level 1 commission field → observe numeric keyboard 7. Click on Level 2 commission field → observe keyboard type 8. Click on Level 3 commission field → observe keyboard type


## ❌ Actual Result
Level 1: numeric keyboard appears

Level 2 & Level 3: normal keyboard appears and allows different input

## ✅ Expected Result
Clicking any commission field for Level 1, Level 2, or Level 3 should consistently open the numeric keyboard, and ahould only allow numeric input as per relevant field

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1wjbnFvW8dgQBevNGiAt9n5YDhYrvI8Bh/view?usp=sharing

