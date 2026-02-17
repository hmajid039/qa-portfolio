**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-06-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When updating the “Business Official Name” field on an individual account profile, the system first shows a success message “Profile saved successfully” and in ~0.15 seconds, an error message (“This name already exists”) appears below the same field. If the user navigates away (e.g., to Contacts) and returns, the error disappears, and saving again only shows the success message.

## 🔁 Steps to Reproduce
1. Log in to the website using an individual user account (user0000, 123123). 2. Navigate to My Account 3. Observe that the field “Business Official Name” is visible. 4. Change the value of this field(unique name) and click Save Changes. 5. Note the messages displayed — “Profile updated successfully” and “This name is already taken.” 6. Navigate and observe that the error disappears, even though the field value remains unchanged.


## ❌ Actual Result
Both success and error messages display, validation error disappears after navigating away and returning.

## ✅ Expected Result
If validation fails, the system should show the error message in case the name is not available and
the validation error should persist consistently until corrected.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1gllt_QIj7iWQPzLcYADS8gr32OPvuK41/view?usp=sharing

