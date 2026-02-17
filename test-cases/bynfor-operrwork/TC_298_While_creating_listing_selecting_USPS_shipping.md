**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-11-03 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
While creating a listing and selecting USPS shipping, the country is auto-selected by default. However, when the user opens the State dropdown, it incorrectly displays country names instead of state names. The issue persists until the user manually reselects the country, which refreshes the state list correctly.

## 🔁 Steps to Reproduce
1. Go to the BynFor app and log in (Account: qacomet3). 2. Start creating a new listing and select USPS as the shipping method. 3. Observe that the Country field is auto-filled. 4. Open the State dropdown without changing the country.


## ❌ Actual Result
The State dropdown displays a list of countries instead of states until the user manually reselects the country

## ✅ Expected Result
The State dropdown should display a list of states corresponding to the preselected country.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1--L3Op2-253_3yC_TzAhF6muZue4bJ5k/view?usp=sharing

