**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-11 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
When the user tries to place a bid in an auction, the system initially shows the validation message “Bid amount should be greater than starting point” even when the entered bid amount is already greater than the starting bid. The message appears first and only then the actual bid process begins, causing confusion and a broken flow.

## 🔁 Steps to Reproduce
1. go to Bynfor and Go to any Auction product listing. 2. Click on Bid. 3. Enter a bid amount greater than the starting bid. 4. Click on Place Bid.


## ❌ Actual Result
The system first displays the validation error “Bid amount should be greater than starting point”, even though the amount entered is already valid. Only after this message, the actual bid process starts.

## ✅ Expected Result
If the bid amount is greater than the starting price, the bid should be accepted immediately without showing any validation message.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1UEwG44tFsPhtgnc4b9FpeaX6hS8TBXkN/view?usp=sharing

