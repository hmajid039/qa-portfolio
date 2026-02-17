**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-11-04 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the Real Estate listing section, the phone number input field allows users to enter excessively long numbers — even beyond 20 digits. This lack of validation can lead to incorrect or invalid contact information being saved, affecting communication between buyers and sellers.

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet3) 2. Navigate to the “Real Estate” category and start creating a listing 3. Locate the phone number input field 4. Enter a number longer than 20 digits 5. Save or continue the listing process


## ❌ Actual Result
The phone number field should restrict input to a valid format (e.g., 10–15 digits maximum, depending on country standards).

## ✅ Expected Result
The system allows users to input and save phone numbers with more than 20 digits without any validation or error message.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1GfTFA_9ypL7qPddrzLJ3dnBTploIMN6N/view?usp=sharing

