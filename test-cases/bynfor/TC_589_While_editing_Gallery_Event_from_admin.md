**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-12-24 00:00:00
**Status:** Open
**Severity:** Low
**Priority:** Medium
**Category:** UI/UX

---

## 🐞 Description
While editing Gallery Event from the admin panel, the content entered in the Privacy Policy field appears in the Description and Programme Overview input fields. This issue occurs on the admin screen, but the admin UI shows incorrect field values, which may lead to accidental data overwrite during edits

## 🔁 Steps to Reproduce
1. Login to Bynfor Admin panel 2. Create a Gallery Event and fill Description, Programme Overview, and Privacy Policy with different content 3. Save the event 4. Click Edit on the created event 5. Observe the ccontent shown in Description and Programme Overview fields


## ❌ Actual Result
Description and Programme Overview fields show Privacy Policy content
instead of their own saved values

## ✅ Expected Result
Each field should display its own previously saved content

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1dB_brV8NruApxAxEet6pi8Yj61zpHx44/view?usp=sharing

