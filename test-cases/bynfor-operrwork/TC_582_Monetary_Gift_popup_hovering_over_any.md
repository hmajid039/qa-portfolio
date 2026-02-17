**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Laptop/Windows 11
**Date:** 22-12-25
**Status:** Open
**Severity:** High
**Priority:** High
**Category:** Security

---

## 🐞 Description
In the Monetary Gift popup, hovering over any clickable or link-like element displays javascript: in the browser status bar. Although the actions work correctly on click, this behavior indicates improper link implementation and may negatively impact user experience and perceived security

## 🔁 Steps to Reproduce
1. Login bynfor dev(majidbusiness / Sun@Ray123), (MajidB / Sun@Ray123) 2. Open chat where a Monetary Gift is received 3. Click View Reward Text to open the Monetary Gift popup  4. Hover over any clickable element in the popup (e.g. “Monetary Gift's transferred to Wallet”, buttons, clickable text) 5. Observe the browser status bar (bottom-left corner)


## ❌ Actual Result
For all clickable elements in the popup, javascript: is displayed in the browser status bar on hover

## ✅ Expected Result
Hovering over clickable elements in the popup should show a valid URL where applicable, or show nothing, not expose javascript: in the browser status bar

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1Rt9o9AQ4mPYufDbDpv2HTTfKwOxloTk2/view?usp=sharing

