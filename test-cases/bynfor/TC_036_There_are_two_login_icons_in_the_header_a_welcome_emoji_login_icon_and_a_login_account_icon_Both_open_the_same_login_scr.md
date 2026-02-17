**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android 13 and Windows 11
**Date:** 2025-10-08 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
There are two login icons in the header: a welcome emoji login icon and a login account icon. Both open the same login screen, which also has the Register page. When using the login account icon with the “Remember Me” functionality, credentials are pre-filled on subsequent visits. However, when using the emoji login icon, the credentials are not pre-filled, even though the same account was used. This causes inconsistent user experience.

## 🔁 Steps to Reproduce
1. Click on the login account icon in the header. 2. Enter valid credentials and select “Remember Me.” 3. Log out or close the application. 4. Click the login account icon again - credentials should be pre-filled (verified). 5. Log out or close again. 6.Click the emoji login icon in the header – credentials are not pre-filled.


## ❌ Actual Result
“Remember Me” works with the login account icon.

“Remember Me” does not work with the emoji login icon.

## ✅ Expected Result
“Remember Me” functionality should work consistently across both login icons, pre-filling credentials regardless of which icon is used.

## 📎 Evidence (Screenshot/Video URI)
Desktop : https://livestore.operrwork.com/operrwork/video/2025__10/2025_10_8__17_33_31__Operr1759944808185.webm   Android: https://drive.google.com/file/d/1ks2HOurgw1_iDb3n228bl1jgyL3k-dHA/view?usp=drive_link

