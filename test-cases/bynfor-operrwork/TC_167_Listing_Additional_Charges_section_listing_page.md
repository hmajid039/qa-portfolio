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
On the Listing Additional Charges section of the listing page, the country-wise charge checkboxes display inconsistent pricing. For Arabic and Hindi countries, the additional charge is shown as $0, while other countries display actual charges. This may confuse sellers and create a perception of unfairness if exemptions are not clearly indicated.

## 🔁 Steps to Reproduce
1. Go to the Bynfor web application and log in. 2. Navigate to Profile → Listing → Create Listing → Additional Charges. 3. Observe the country-wise translate additional charge checkboxes. 4. Compare the displayed charges for Arabic and Hindi countries versus other countries.


## ❌ Actual Result
Arabic and Hindi countries show an additional charge of $0.

Other countries show non-zero charges.

There is no indication or message explaining why some countries are exempt.

## ✅ Expected Result
All countries should display the correct additional charges based on the system configuration.

If certain countries (e.g., Arabic or Hindi) are exempt from additional charges, this should be clearly indicated in the UI to avoid confusion or perceived unfairness.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1nS03I1aj6vXgOm4WLsXVwB03sKcM-t2u/view?usp=sharing

