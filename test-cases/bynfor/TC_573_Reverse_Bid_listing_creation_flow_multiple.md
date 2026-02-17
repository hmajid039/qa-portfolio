**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop/Windows 11
**Date:** 18-12-25
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
In the Reverse Bid listing creation flow, multiple fields such as Estimate Value(Lower/Highest), and Buyer’s Premium appear to follow normal auction terminology and behavior. While Starting Price and Condition can be acceptable with adjusted meaning, the remaining fields lack reverse-bid-specific logic and labeling. This may confuse users and lead to incorrect assumptions about how reverse bidding works

## 🔁 Steps to Reproduce
1. Open the Bynfor web dev(MajidB / Sun@Ray23) 2. Navigate to Create a Listing from summary 3. Select Reverse Bid as the listing type 4. Review the fields displayed on the form


## ❌ Actual Result
Fields are displayed with normal auction terminology and explanations, which do not clearly align with reverse bidding behavior

## ✅ Expected Result
Reverse Bid listing fields should use terminology, tooltips, and logic specific to reverse bidding, or non-applicable normal auction fields should be hidden or relabeled to prevent user confusion

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1Mfn4m6EJsqMei5Kp3EqnCj8iizyLZxIw/view?usp=sharing

