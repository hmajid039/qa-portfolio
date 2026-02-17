**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-12-24 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
The EIN number entered and accepted during account registration is auto-populated on the Store creation page. However, when the user submits the Store form, the system throws an error stating that the EIN already exists, blocking Store creation.

## 🔁 Steps to Reproduce
1. Go to BynFor QA  and log in (Account: qatest120) 2. Create a new account and enter a valid EIN number during registration 3. Proceed to Create Store 4. Observe the EIN field auto-filled with the registered EIN 5. Fill all other required Store details 6. Submit the Store creation form


## ❌ Actual Result
System shows error message: “EIN already present, use another one” and Store is not created.

## ✅ Expected Result
The auto-filled EIN (already linked to the account) should be accepted and Store creation should succeed.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1buyAL1-8VgByKAuIvU_nEkJG2JpKMJ9o/view?usp=sharing

