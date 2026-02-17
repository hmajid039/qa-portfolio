**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11 Pro
**Date:** 2025-10-07 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
The hover/clickable area for the language selector on the login popup is too large. When the mouse is moved near the close (X) button, it changes to a pointer and opens the language list unintentionally, which interferes with normal user interaction.

## 🔁 Steps to Reproduce
1. Go to "https://dev.bynfor.com/home"   2.Click Sign In to open the login popup 3.Move the mouse cursor near the close (X) button at the top-right of the popup  4.Observe the cursor and the behavior of the language selector


## ❌ Actual Result
When the cursor is moved near the close (X) button, it changes to a hand pointer, and the language list opens automatically due to the oversized clickable area of the language selector.

## ✅ Expected Result
The clickable area for the language selector should be limited to the visible language icon/text only, and hovering near the close (X) button should not trigger the language dropdown.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1kpK9ibl76wMEZx2p2DXLA0s2lscByToe/view?usp=drive_link

