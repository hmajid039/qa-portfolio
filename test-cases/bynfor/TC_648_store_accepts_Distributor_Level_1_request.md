**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-12-31 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a store accepts a Distributor Level 1 request under the Partnership Programme, the distributor receives a notification with incorrect text. The word “Admin” is repeated twice, and the placeholder {{name}} is not replaced with the actual registered name.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in(Qacomet1) 2. Navigate to Partnership Programme 3. Accept a Distributor Level 1 request 4. Log in from the Distributor account 5. Check notifications


## ❌ Actual Result
Notification shows:
“Admin Admin has approved you as become partner with the registered name qacomet3 you as become partner with the name {{name}}”

## ✅ Expected Result
Notification should display correct grammar, single Admin, and replace {{name}} with the actual registered partner name.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1o_Htr_gU3dZ1PcttSnWk2TSwFZe20rC2/view?usp=sharing

