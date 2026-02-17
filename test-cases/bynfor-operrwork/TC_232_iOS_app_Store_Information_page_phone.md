**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-28 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the iOS app Store Information page, the phone number input field allows users to enter more than 10 digits without displaying any validation message. This can lead to submission of invalid contact numbers and data inconsistency in the business profile.

## 🔁 Steps to Reproduce
1. Open the iOS app. 2. Log in with a Business Account. 3. Navigate to the Store Information page. 4. Enter a phone number longer than 10 digits (e.g., 9876543210123). 5. Try to save or move to the next field.


## ❌ Actual Result
The system accepts phone numbers longer than 10 digits without showing any validation error.

## ✅ Expected Result
The phone number field should restrict input to a maximum of 10 digits and display a validation message such as “Please enter a valid 10-digit phone number.”

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1PdHNidxUv0uV9jVPSvexq_qflcBCasLS/view?usp=sharing

