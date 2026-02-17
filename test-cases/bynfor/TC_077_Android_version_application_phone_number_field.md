**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Responsive Design Bug
**Date:** 2025-10-13 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the Android version of the application, the phone number field in the selling section does not properly display the entire number.
When a user enters a 10-digit phone number, the system accepts it successfully, but due to a locked area (such as the country code or prefix), part of the phone number is hidden.
To view the full number, the user must scroll left and right, which impacts usability and user experience.

## 🔁 Steps to Reproduce
1. Open the application on an Android device. 2. Navigate to the Selling section. 3. Enter a valid 10-digit phone number. 4. Observe that the number is accepted but not fully visible on the screen. 5. Try to view the entire number — notice that horizontal scrolling is required to see all digits.


## ❌ Actual Result
1. Phone number field does not display the entire number at once.
2. Part of the number is hidden due to the locked area before the phone number.
3. Users must scroll left/right to see the complete number.

## ✅ Expected Result
1. The entire phone number should be fully visible within the input field without requiring scrolling.
2. The field should dynamically adjust to show the complete number along with the code/prefix.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1xVdDyAqlt4p-On3ube2uonJF_kolaOMI/view?usp=drive_link

