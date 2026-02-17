**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-16 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
During Business Account Registration, when the user selects “Insurance Company” as the business type, a dropdown field “Types of Insurance*” appears with multiple checkbox options. However, clicking on the text label beside any checkbox also toggles the selection state, instead of only responding to clicks on the checkbox itself.

## 🔁 Steps to Reproduce
1. Go to the Registration page. 2. Select Business Account. 3. In the Business Type dropdown, choose Insurance Company. 4. Observe the “Types of Insurance*” dropdown field that appears. 5. Click on the text label beside any checkbox instead of the checkbox itself.


## ❌ Actual Result
The checkbox gets selected/deselected even when the user clicks on the text label beside it.

## ✅ Expected Result
Checkboxes should only be selected or deselected when the checkbox itself is clicked — not when the text beside it is clicked.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/13GV_wgVzFNEBu2xSwwfHFajFLkWl4Qfv/view?usp=sharing

