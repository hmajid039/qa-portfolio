**Reported By:** Majid Ali
**Environment:** Staging
**Device:** android 15
**Date:** 2025-10-12 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
When tapping on the Register button for the Membership(e.g: Temporary), the app takes around 10–12 seconds to navigate to the Payment Information page. This delay is so long that it appears as if the button is unresponsive

## 🔁 Steps to Reproduce
1. Open the Bynfor app android(appuser / Sun@Ray123) 2. Go to Summary -> Membership 3. Navigate to Packages tab 4. Tap on Register 5. Observe the delay of 10–12 seconds before the Payment Information page appears


## ❌ Actual Result
Payment Information page appears only after 10–12 seconds, no loading indicator or feedback during the delay, user may think the button is not working and try other memberships, causing UI confusion and inconsistent navigation

## ✅ Expected Result
Navigation to Payment Information page should occur within 2–3 seconds. If backend processing is slow, a loading spinner should be shown to indicate progress

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/11pxgHSLJaNxqKrle5aQvdyyGfefepba1/view?usp=sharing

