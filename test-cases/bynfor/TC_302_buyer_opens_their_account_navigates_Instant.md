**Reported By:** Majid Ali
**Environment:** Staging
**Device:** ios 18.5
**Date:** 2025-10-03 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When a buyer opens their account and navigates to the Instant Buy section, the Subscribe button at the bottom of a listed product behaves inconsistently. In some cases, it appears already subscribed (green) and shows “Successfully unsubscribed” upon clicking. Other times, it appears grey even when the user is already subscribed. and clicking upon it shows you are successfully unsubscribed. This inconsistency creates confusion about the actual subscription state of the product.

## 🔁 Steps to Reproduce
1. Go to the BynFor app and log in as a buyer.(Nikitatesteraccount) 2. Navigate to the Instant Buy section. 3. Open any listed product. 4. Observe the Subscribe button’s color and behavior when clicked.


## ❌ Actual Result
1. The Subscribe button sometimes appears green (already subscribed) even before user action, and clicking it immediately unsubscribes. In other cases, it appears grey but still behaves inconsistently when clicked.   2. User is by default subscribed.

## ✅ Expected Result
1. The Subscribe button should consistently reflect the correct subscription state:

Green (subscribed)

Grey (unsubscribed)
and update accurately after interaction.

2. The user should not be pre-subscribed by default; the subscription should occur only when the user actively clicks Subscribe.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1gh193cz1jeqx6mbQFuBGHWbPgcqhfrjE/view?usp=sharing

