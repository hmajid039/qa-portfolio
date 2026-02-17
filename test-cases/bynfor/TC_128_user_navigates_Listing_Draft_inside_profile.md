**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-10-15 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a user navigates to Listing → Draft inside the profile icon, the Duration dropdown initially displays the previously chosen duration. However, after a few seconds, the displayed value disappears, even though the calculated duration date below still reflects the selected duration

## 🔁 Steps to Reproduce
1. Go to the Bynfor web application and log in. 2. Click on the Profile icon and then click on the Listing button. 3. Open any draft listing. 4. Observe the Duration dropdown; note that it initially shows the previously selected duration. 5. Wait a few seconds and observe that the dropdown value disappears, even though the calculated duration date below remains visible.


## ❌ Actual Result
The Duration dropdown loses the displayed value after initial load, while the duration date below remains correct.

## ✅ Expected Result
The Duration dropdown should consistently display the selected duration and remain synchronized with the calculated duration date.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1dtwmX2_oHtsVEMXq9OsuY1Wvo-Ar2L3H/view?usp=sharing

