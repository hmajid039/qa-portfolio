**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-17 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the USPS Shipping edit page in the Create Listing functionality, when a user selects the origin country for shipping, the State field is automatically populated. This behavior is incorrect, as the state should not be auto-selected. Users should manually select the state after choosing the country to avoid incorrect shipping information.

## 🔁 Steps to Reproduce
1.Go to the Bynfor web application and log in. 2. Navigate to Profile → Listing → Create Listing → USPS Shipping Edit Page. 3. Select a country in the Origin of Shipping dropdown. 4. Observe the State field after selecting the country.


## ❌ Actual Result
The State field is automatically selected/populated immediately after choosing the country.

## ✅ Expected Result
The State field should remain empty until the user manually selects the desired state after selecting the country.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1-7I-Ja4d-MXhSV3K3pkIKe-oxQa_IbDM/view?usp=sharing

