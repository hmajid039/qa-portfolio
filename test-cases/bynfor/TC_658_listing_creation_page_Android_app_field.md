**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 2025-12-31 00:00:00
**Status:** Open
**Severity:** Low
**Priority:** Medium
**Category:** UI/UX

---

## 🐞 Description
On the listing creation page of the Android app, the field “Would you like to translate your listing for additional cost?” is marked with an asterisk (*) indicating that it is mandatory. However, the listing can be successfully created without selecting any language.

Additionally, the Instruction field shows the asterisk inside the placeholder text (“Instruction*”) instead of properly marking the field as required, which can confuse users about which fields are mandatory.

## 🔁 Steps to Reproduce
1. Open Bynfor Android app (majidbusiness / Sun@Ray123) 2. Go to Seller Area → My Listing → Create new listing 3. Fill other required listing details 4. Leave the “Would you like to translate your listing for additional cost?” field unselected 5. Observe that the Instruction field shows placeholder “Instruction*”


## ❌ Actual Result
Listing is created successfully without selecting a language which is marked with *

Instruction field placeholder shows “Instruction*” instead of properly marking it as required

## ✅ Expected Result
The system should prevent listing creation if the field is mandatory and if not, then no visible indicators(*) should be there

The asterisk should be visibly associated with the field label, not inside placeholder text

UX should clearly indicate which fields are mandatory

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/138Iy3Xtn1MDZTMD73PrT0DcKB9OJNDo2/view?usp=sharing

