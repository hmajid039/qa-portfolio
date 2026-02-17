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
On the Listing page, when attempting to change the category or subcategory, the dropdowns incorrectly display nested categories (e.g., main categories containing subcategories inside them). Additionally, the subcategory dropdown shows nested selections of the already selected category, which causes confusion and poor usability. These dropdowns should display simple, non-nested lists for easy selection.

## 🔁 Steps to Reproduce
1. Go to the Bynfor web application and log in. 2. Navigate to Profile → Listing → create a listing and select the detailed listing. 3. Click on the Category dropdown and observe the structure. 4. Click on the Subcategory dropdown and observe the selections shown


## ❌ Actual Result
Both the Category and Subcategory dropdowns display nested options, showing categories within categories and previously selected items as nested.

## ✅ Expected Result
The Category and Subcategory dropdowns should display flat, simple lists without nested selections.
In the Category dropdown, only the list of main categories should be shown for direct selection.
In the Subcategory dropdown, only the subcategory options related to the selected category should be displayed in a simple list — not nested or repeated.

## 📎 Evidence (Screenshot/Video URI)
https://livestore.operrwork.com/operrwork/video/2025__10/2025_10_17__17_0_54__Operr1760720450655.webm

