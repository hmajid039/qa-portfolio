**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-12-12 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the Real Estate listing form, the Secondary Email field accepts plain characters and does not validate proper email format (e.g., missing “@” and domain).

## 🔁 Steps to Reproduce
1. Log in to BynFor 2. Go to Create Real Estate Listing 3. Enter random characters (e.g., “abcde”) in the Secondary Email field 4. Submit the form


## ❌ Actual Result
Field accepts invalid input with no email format validation.

## ✅ Expected Result
Secondary Email should validate proper email format (e.g., name@example.com
) and show an error for invalid entries.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1F5uKsScZCDJR6asuPF__Rs_gpNTZIE_F/view?usp=sharing

