**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 2025-11-18 00:00:00
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Security

---

## 🐞 Description
When the user creates an auction listing that ends without any bids and then goes to the Ended Listings page to clone it, the Auction End Date field does not get auto-filled or disabled (faded) as expected.
The field stays active but neither accepts keyboard input nor opens the calendar selector, making it impossible for the user to set a new auction end date. Because of this, the user cannot complete the cloning process

## 🔁 Steps to Reproduce
1. Go to BynFor app and log in (Account: qacomet3) 2. Create a new Auction Listing 3. Let the auction end without any bids 4. Navigate to the Ended Listings page 5. Select the ended auction listing and click Clone Listing 6. Try to update the Auction End Date field


## ❌ Actual Result
Auction End Date field is not auto-filled

Calendar picker does not open

Keyboard input does not work

User cannot enter or modify the date

Listing cannot be cloned

## ✅ Expected Result
The Auction End Date field should either:

auto-fill with a valid default date, or

allow the user to update it via calendar picker or keyboard input
so the listing can be cloned successfully.

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1dO4KHSg1DGQ2zkjcnYwa_wzXR5tmEJIT/view?usp=sharing

