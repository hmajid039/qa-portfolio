**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-06 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
The tooltip for “Best Offer” displays incorrect content in the manual section. It currently states: "If there is reserve price then all offers below reserve price will be rejected." This content is intended for the automatic section, not manual. This can confuse users about how manual offers are handled.

## 🔁 Steps to Reproduce
1. Go to Bynfor web (Account used: qacomet3)                               Navigate to the Best Offer section in the application. 3. Hover over the tooltip for “Manual” offer. 4. Observe the content displayed inside the tooltip. 5. Compare it with the intended description for manual vs automatic offers.


## ❌ Actual Result
The tooltip under “Manual” incorrectly shows: "If there is reserve price then all offers below reserve price will be rejected," which belongs to automatic offers.

## ✅ Expected Result
The tooltip under “Manual” should display content relevant to manual offers only. The reserve price note should appear under the automatic section.

## 📎 Evidence (Screenshot/Video URI)
https://livestore.operrwork.com/operrwork/video/2025__11/2025_11_6__16_27_45__Operr1762446463592.webm

