**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-18 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a user creates a new group, the system immediately displays a ‘Remove From Group’ button under the Target Group section, even though no contact has been added to that group.
Clicking the button triggers a toast message stating:
“Contact is removed from the group 'group name'”

## 🔁 Steps to Reproduce
1. Login to the website (majidbusiness/Sun@Ray123)               2.Navigate to My Account → Groups 3.Click Create New and create any group (e.g., Auction1) 4.Observe the Target Group section 5.A “Remove From Group” button appears automatically 6.Click on the “Remove From Group” button


## ❌ Actual Result
The Remove From Group button is visible even when the group is empty
Clicking it shows a toast:
“Contact is removed from the group”

## ✅ Expected Result
Remove From Group button should not appear unless:
At least one contact is added to the group
If no contact exists, the button should be hidden or disabled
No removal toast should appear for an empty group

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1E9b0gzmOmNnOR7XHavfcbhns00pmyDxh/view?usp=drive_link

