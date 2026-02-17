**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop/Windows 11
**Date:** 2025-10-13 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When switching the input type from Email or Username to Phone Number in the “Forgot Username or Password” popup, the instruction text still mentions “email” instead of updating to “phone”. This causes confusion about how the recovery information will be sent.

## 🔁 Steps to Reproduce
1.Go to the login popup.   2.Click on “Forgot Username or Password?”.   3. Select Password under “I Forgot My”.   4.Switch Input Type from “Email or Username” to “Phone Number”.


## ❌ Actual Result
The text below still says:                      Forgot your username? We will email it to the address we have.      Forgot your password? We can send a verification code to your email.

## ✅ Expected Result
When Phone Number is selected, the text should update to:                         Forgot your username? We will send it to the phone number we have.           Forgot your password? We can send a verification code to your phone.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/12BWyCjUQbJO8EOyELXfbT37qpHXpVozV/view?usp=drive_link

