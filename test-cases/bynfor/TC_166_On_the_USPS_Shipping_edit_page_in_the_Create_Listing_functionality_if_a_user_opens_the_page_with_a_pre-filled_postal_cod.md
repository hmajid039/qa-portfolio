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
On the USPS Shipping edit page in the Create Listing functionality, if a user opens the page with a pre-filled postal code (e.g., 6 digits), deletes it, and then selects the same or different country, the Postal Code field restricts entry to only 5 digits. This prevents users from entering valid longer postal codes (e.g., 6 digits or ZIP+4 for USPS), creating an inconsistent and confusing behavior.

## 🔁 Steps to Reproduce
1. Go to the Bynfor web application and log in. 2. Navigate to Profile → Listing → Create Listing → USPS Shipping Edit Page. 3. Open the page with a pre-filled Postal Code (e.g., 6 digits). 4. Delete the existing postal code. 5. Select either the same country or a different country in the origin dropdown. 6. Attempt to enter the postal code again.


## ❌ Actual Result
The Postal Code field now restricts input to 5 digits, preventing entry of longer valid postal codes.

## ✅ Expected Result
The Postal Code field should allow entry of the full valid postal code based on the selected country, regardless of previous values.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1bF1_VbD_uT6yaes2f2sC8ai0hNhGGuqz/view?usp=sharing

