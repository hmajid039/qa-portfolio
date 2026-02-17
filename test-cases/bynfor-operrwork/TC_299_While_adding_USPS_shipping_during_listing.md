**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-11-03 00:00:00
**Status:** Open
**Severity:** Low
**Priority:** Medium
**Category:** UI/UX

---

## 🐞 Description
While adding USPS shipping during listing creation, the Zip Code field is not mandatory. When the user fills all other required details and clicks on Calculate, no validation message appears, and no calculation or action is performed. This creates confusion for users and prevents them from completing the shipping setup.

## 🔁 Steps to Reproduce
1. Go to the BynFor app and log in (Account: qacomet3). 2. Start creating a new listing and select USPS as the shipping method. 3. Fill all required shipping details except the Zip Code. 4. Click on Calculate.


## ❌ Actual Result
No error message appears, and the Calculate button performs no action when the Zip Code field is left blank

## ✅ Expected Result
The system should either make the Zip Code field mandatory and show an appropriate validation message if left empty, or handle the calculation properly using available data.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1KVR6Eb4zLZazjQ9dyhifoLOFwTTwJyLv/view?usp=sharing

