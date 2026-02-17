**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a gift card is received after purchasing a membership, the validity line incorrectly displays the variable placeholder {{expiredDate}}. This suggests the date label text is not properly rendered, which can confuse users or make the interface appear broken

## 🔁 Steps to Reproduce
1. Log in (majidbusiness, Sun@Ray123) on the bynfor website 2. Go to My Account → Membership 3. Purchase a membership 4. Go to the gift cards section pf the wallet 5. Observe the validity liine showing {{expiredDate}}"


## ❌ Actual Result
The text displays as: Valid until {{expiredDate}}: November 11, 2025

## ✅ Expected Result
The placeholder should not be displayed

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1pPH14UnN13RQjio0s9RO-go3jTUDZx8B/view?usp=sharing

