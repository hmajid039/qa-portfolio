**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop/Windows 11
**Date:** 18-12-25
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Payments

---

## 🐞 Description
In a Reverse Bid auction, the “winning payment” explanation popup and the “Who is eligible?” (Skill Rewards) text appear to be reused from a normal Sealed bid auction and are incorrect for reverse bidding: The logic matches normal sealed bid (second‑price) logic, not a reverse auction.
The wording (“Second Highest Bidder”) does not match Reverse bid logic and terminology (where the key values are lowest and second‑lowest bids)

## 🔁 Steps to Reproduce
1. Open the Bynfor web dev(MajidB / Sun@Ray23) 2. Navigate to Create a Listing from summary 3. Create a Reverse Bid listing with Starting Price = 17,000 4. Place a bid: 16,000(MajidA / Sun@Ray123) 5. Observe the winning payment popup 6. Check bidder Skill Rewards logic


## ❌ Actual Result
This is a reverse bid (bids go down, lowest bid wins).
With winning bid = 16,000 and second highest bid = 17,000, the popup says the winning payment is 17,700, which is:
Higher than the starting price (17,000),
Higher than the second highest bid (17,000),
Higher than the winning (lowest) bid (16,000).
This behaviour matches a forward Sealed bid auction, not a reverse auction where the buyer usually benefits from the lowest bid

## ✅ Expected Result
Logic should be aligned with Reverse Bid behaviour, the explanation should use a formula and example that make sense when bids decrease and the lowest bid wins;
The winning payment should not appear to be higher than both the winning (lowest) bid and the second highest bid unless this is explicitly intended by the product design

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1rZGHs6kacfymXdfco43GR5rrtyQ7TMRb/view?usp=sharing

