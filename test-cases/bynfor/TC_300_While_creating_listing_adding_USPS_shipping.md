**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-11-03 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While creating a listing and adding USPS shipping, the system displays an error message — “Please provide correct Zip for sender” — even when the correct ZIP Code matching the selected state is entered. This prevents users from proceeding with USPS shipping setup and calculating shipping rates correctly.

## 🔁 Steps to Reproduce
1. Go to the BynFor app and log in (Account: qacomet3). 2. Start creating a new listing. 3. Select USPS as the shipping method. 4. Enter a valid ZIP Code corresponding to the selected state. 5.Click on Calculate.


## ❌ Actual Result
The system incorrectly shows an error message — “Please provide correct Zip for sender” — even for valid ZIP Codes, blocking the calculation process.

## ✅ Expected Result
The system should accept a valid ZIP Code that matches the selected state and proceed to calculate shipping rates successfully.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1va4vaAJFoiRhALObjrlZ769no8_aMox7/view?usp=sharing

