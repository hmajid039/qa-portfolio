**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop / Windows 11
**Date:** 2025-12-30 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When clicking the “Pay Nominal Verification Fee” button on a submitted partner application, the system displays the message “Become partner updated successfully.” This message is misleading, as no application details are updated during this action

## 🔁 Steps to Reproduce
1. Log in to the Bynfor dev website as Account A 2. Submit a partner application for review 3. Ensure status is Pending 4. Click on “Pay Nominal Verification Fee” 5. Observe the success message displayed


## ❌ Actual Result
The message “Become partner updated successfully” is shown when navigating to the payment page

## ✅ Expected Result
A relevant message should be shown, such as:
“Redirecting to payment”
“Proceed to verification fee payment”
Or no success message should be shown if no update occurs

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1oROlFrEgrI3P-mwylU0aAsMTLyYwK23u/view?usp=sharing

