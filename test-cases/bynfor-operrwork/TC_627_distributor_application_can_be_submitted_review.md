**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-12-29 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
The distributor application can be submitted for review without checking the acknowledgement checkbox stating “I understand I will not get commission before I pay for the nominal verification fee.” and allows users to proceed and get approved without checking it. After approval, the checkbox becomes disabled, and the “Pay Verification Fee” button remains visible. While the system may enforces rules via payment, the flow make it difficult for users about when and why they need to pay

## 🔁 Steps to Reproduce
1. Log in to the Bynfor dev website 2. Navigate to Partnership Programs → Distributor Partnership 3. Fill required fields 4. Leave the acknowledgement checkbox unchecked 5. Click Submit for Review 6. Approve the request from another business account


## ❌ Actual Result
The application is successfully submitted and approved without the user accepting the acknowledgement

## ✅ Expected Result
The system should block submission and display an error until the acknowledgement checkbox is checked

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1FeVtlQ7oWH87meRAUD6x-9utidmUp1T3/view?usp=sharing

