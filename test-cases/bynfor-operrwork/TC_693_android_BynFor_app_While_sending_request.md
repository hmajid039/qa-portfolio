**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Android Phone
**Date:** 2026-01-06 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the android BynFor app, While sending a request from an individual account to a business account in the BynFor Android app, the Country and State fields were not selected. Despite this, the request was successfully sent. After the request was sent, the Country and State fields were automatically filled without any user input.

## 🔁 Steps to Reproduce
1- Login to the BynFor Android app using an individual account 2- Navigate to send a request to a business account 3- Do not select Country or State 4- Submit the request


## ❌ Actual Result
The request is sent successfully without selecting Country and State. After submission, both fields are automatically populated by the system.

## ✅ Expected Result
The request should not be sent unless the Country and State fields are selected. The system should not auto-fill these fields without user input.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1Hl6ACJ7NnFpjxnnc44BJ1v3eBwyGsAZc/view?usp=drive_link

