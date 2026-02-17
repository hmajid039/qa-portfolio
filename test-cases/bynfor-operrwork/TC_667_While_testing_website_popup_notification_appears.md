**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2026-01-02 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While testing the website, a popup notification appears on the Edit option of an active listing stating that the listing can only be revoked or updated within 30 minutes. However, the listing was created on 31 December, and editing is still allowed even after the 30-minute limit has passed. This behavior is inconsistent with the popup message.

## 🔁 Steps to Reproduce
1. Log in to the business account (majidbusiness / Sun@Ray123) 2. Go to Active Listings 3. Open a listing created on 31 December 4. Click on the Edit option


## ❌ Actual Result
The system shows a popup saying the listing can only be updated or revoked within 30 minutes, but still allows editing after the time limit has exceeded.

## ✅ Expected Result
The system should either block editing after 30 minutes or update the popup message to reflect the correct editing policy.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1pIM3G6QjKPW6JASiUr95oRGrEYDzX1ir/view?usp=drive_link

