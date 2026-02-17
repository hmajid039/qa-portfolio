**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Responsive Design Bug
**Date:** 2025-10-13 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Functional

---

## 🐞 Description
On the Android version of the application, under Selling, the Map upload functionality displays a popup error before the map loads.
The popup reads: “This page cannot load Google Maps. Do you own this website?”
The map only becomes visible after the user clicks “OK” on the popup.

## 🔁 Steps to Reproduce
1. Open the application on an Android device. 2. Navigate to Selling → My Store. 3. Attempt to view or upload the store location using the Map. 4. Observe that a popup appears above the map with the message: “This page cannot load Google Maps. Do you own this website?” 5. Click OK on the popup. 6.The map becomes visible and functional only after dismissing the popup.


## ❌ Actual Result
Popup error appears before the map loads.

Map is not visible until the user clicks OK.

Causes poor user experience and confusion.

## ✅ Expected Result
Map should load directly without displaying the error popup.

Users should be able to interact with the map seamlessly.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1Dv9fTelzLEFTKdR1G99OSvZKlu8siYkH/view?usp=sharing

