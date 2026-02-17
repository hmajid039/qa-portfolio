**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-28 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the iOS app Store Information page, the “View My Store” button is displayed at the top even when the user hasn’t filled out or saved any store information yet. When the user taps this button, it incorrectly redirects to another seller’s store page

## 🔁 Steps to Reproduce
1. Open the iOS app. 2. Log in with a new or existing Business Account that has not created a store yet. 3. Navigate to the Store Information page. 4. Observe the “View My Store” button displayed at the top. 5. Tap on the “View My Store” button.


## ❌ Actual Result
The “View My Store” button is visible even before store setup, and tapping it redirects to another seller’s store instead of the logged-in user’s store.

## ✅ Expected Result
The “View My Store” button should be hidden or disabled until the user has successfully created and saved their own store information.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1YWjTWuiHYB16bJ8Tk-CzD61IShI8f-UK/view?usp=sharing

