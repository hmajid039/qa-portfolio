**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Responsive Design Bug
**Date:** 2025-10-13 00:00:00
**Status:** Open
**Severity:** Medium
**Priority:** Medium
**Category:** Functional

---

## 🐞 Description
On the Android version of the application, the login page becomes unresponsive while attempting to log in.
A username that successfully logs in on the Desktop version shows “Username not found” on Android. This behavior indicates inconsistency in the backend database synchronization or user authentication system across platforms.

## 🔁 Steps to Reproduce
1. Open the application on an Android device. 2. Go to the login page. 3. Enter a valid username and password that is already logged in successfully on Desktop. 4.Tap the Login button. 5. Observe that the page becomes unresponsive for a few seconds. 6. After refreshing or retrying, observe that the system displays “Username not found”.


## ❌ Actual Result
Android login page becomes unresponsive during login attempt.

Displays “Username not found” for valid credentials that work on Desktop.

## ✅ Expected Result
Android login should respond promptly.

System should consistently recognize valid usernames and allow successful login, matching Desktop behavior.

## 📎 Evidence (Screenshot/Video URI)
Android : https://drive.google.com/file/d/1PwtuTqo3Ii81v2biWlWTSFb66O9bC2Yq/view?usp=sharing         Desktop : Desktop : https://livestore.operrwork.com/operrwork/video/2025__10/2025_10_13__15_31_52__Operr1760369508217.webm

