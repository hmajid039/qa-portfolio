**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-05-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a user searches for a contact using the search bar on the “Search/Add Users” page, the result count label does not update once the search text is cleared. It continues to display the total number if you click on find with empty search box.

## 🔁 Steps to Reproduce
1.Log in to the website (any valid user). 2. Navigate to My Account → Contacts → Search/Add Users. 3. Search for "ma", the count updates 4. Now clear search and click on find 5.Observe that the result shows “No matching results”, but the result count still shows the old number.


## ❌ Actual Result
The result count does not update or reset when you search with no input and shows previos count

## ✅ Expected Result
The count should update for the result text in relation to the results shown below the search bar

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1iJXMR2Lm2FsxowZgmPlyF9VgpyHdOyS4/view?usp=sharing

