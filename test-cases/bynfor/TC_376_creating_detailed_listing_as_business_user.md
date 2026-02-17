**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-12-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When creating a detailed listing as a business user, clicking the Category field sometimes redirects the user to the homepage instead of displaying the listing details. The issue occurs intermittently and resolves temporarily after refreshing the page (might be frontend routing error or session state issue). This unexpected redirection can interrupt the listing creation process

## 🔁 Steps to Reproduce
1. Log in as a business user (majidbusiness / Sun@Ray123). 2. Navigate to My Listings → Create Detailed Listing. 3. Click on the category field to open the dropdown. 5. Observe that sometimes the page redirects to the homepage unexpectedly 6. Refresh the page and try again; it may or may not occur after reload


## ❌ Actual Result
Page redirects to homepage immediately after clicking category

## ✅ Expected Result
The category dropdown should open normally, allowing category selection, without leaving the listing creation page

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1xYwtbKqogq8VAwpRecRtpZ-47ruj1ZpE/view?usp=sharing

