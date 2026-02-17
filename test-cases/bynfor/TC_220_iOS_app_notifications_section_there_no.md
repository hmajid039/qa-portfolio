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
In the iOS app notifications section, when there are no notifications (count = 0), the “Delete” button is still clickable.

## 🔁 Steps to Reproduce
1. Open the iOS app. 2. Login and navigate to the Notifications section. 3. Ensure there are 0 notifications. 4. Click on the “Delete” button.


## ❌ Actual Result
The “Delete” button remains active and can be clicked even though there are no notifications to delete.

## ✅ Expected Result
The “Delete” button should be disabled or hidden when the notification count is 0.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1nL83xmpq8M5YvPqhZlxGk0DZBza-pLDQ/view?usp=sharing

