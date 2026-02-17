**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop/Windows 11
**Date:** 2025-12-12 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When applying filters on the Real Estate listings page, sometimes no matching results are shown even when listings exist for the filter criteria occuring intermittently and often happens after search results show no match

## 🔁 Steps to Reproduce
1. Log in to Bynfor (userbuyer / user@123) 2. Go to Real Estate listing page 3. Apply filters that produce no matches (e.g., Country: USA, State: New York, Price: 500) 4. Observe “No matching listings found” message 5. Remove previous filters and apply valid filters with existing listings (e.g., correct country, state) 6. Observe that sometimes the matching listings do not appear multiple times


## ❌ Actual Result
Sometimes, the listings matching the applied filters do not display, even though they exist. The page may intermittently fail to refresh results or apply filters correctly

## ✅ Expected Result
The listings page should always display results according to the applied filters. Only listings matching the selected criteria should appear, and "No matching listings found" should only appear when no actual matches exist

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1Om2LSvWLu4L_0nfRdqL-lbzEqzCc-t8m/view?usp=sharing                https://drive.google.com/file/d/1EdVD0mPobXn3aTygxegDPDTUOaxDd714/view?usp=sharing

