**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop/Windows 11
**Date:** 2025-10-13 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the desktop version of the application, the username database is not maintaining user data properly.
Initially, while trying to log in with the Personal Account, the system displayed “Username does not exist”, but after a few attempts, I was suddenly able to log in without any change in credentials.
Later, when attempting to log in with the Business Account, the same issue occurred — this time it continuously showed “Username does not exist” and did not allow login at all.
This behavior indicates inconsistency in the backend database or user authentication system.

## 🔁 Steps to Reproduce
1. Open the web application on the desktop browser. 2. Go to the login page. 3. Try logging in with an existing Personal Account username and password. 4. Observe that initially, it shows “Username does not exist,” but after a few tries, it allows login. 5. Now switch to Business Account login. 6. Enter valid existing credentials. 7.Observe that it repeatedly shows “Username does not exist.”


## ❌ Actual Result
For Personal Account: Initially fails to recognize the username but later allows login.

For Business Account: Continuously fails to recognize the username, displaying “Username does not exist.”.

## ✅ Expected Result
System should consistently recognize valid usernames for both Personal and Business accounts and allow successful login without random inconsistencies.

## 📎 Evidence (Screenshot/Video URI)

