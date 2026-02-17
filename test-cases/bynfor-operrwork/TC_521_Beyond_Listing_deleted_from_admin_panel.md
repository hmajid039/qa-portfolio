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
When a Beyond Listing is deleted from the admin panel, the status correctly shows as Deleted on BynFor Dev. However, clicking on the deleted listing redirects the user to a completely different PLP instead of preventing access.

## 🔁 Steps to Reproduce
1. Go to BynFor and log in (Account: qacomet3) 2. Create any Beyond Listing 3. Ask admin to delete that listing 4. Go to BynFor Dev → Beyond Listing section 5. Click on the listing that now shows Deleted status


## ❌ Actual Result
Clicking the deleted listing redirects to another PLP (incorrect page)

## ✅ Expected Result
Deleted listings should not redirect to other PLPs. User should either see “This listing is no longer available” or be prevented from opening it.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1v4_8B-HppUqS9NF7Yh7lGLbT0I1TyYYU/view?usp=sharing

