**Reported By:** Majid Ali
**Environment:** Staging
**Device:** Desktop+Windows 11
**Date:** 14-11-25
**Status:** Open
**Severity:** Low
**Priority:** Medium
**Category:** UI/UX

---

## 🐞 Description
When viewing a dispute case and uploading multiple files, the user is able to delete one of the uploaded files. A toast message correctly displays “Deleted file successfully.”
However, after submitting and checking the case again from both the business and buyer sides, the deleted file still appears in the files section.
This indicates that the file deletion might not actually be applied on the backend or not reflected in the UI after submission

## 🔁 Steps to Reproduce
1. Log in as Business(majidbusiness/Sun@Ray123) 2. Navigate to My Account → Dispute Center 3. Open any dispute → Click the eye icon to view details. 4. Add a message and upload two files 5. Delete one of the files before submitting 6. Observe the toast message: “Deleted file successfully” on top right corner 7. Click Submit 8. Refresh and re-open the same case from business side and view files 9. Log in as buyer, open the same dispute and check files uploaded


## ❌ Actual Result
Both the originally uploaded files are still visible on both business side and buyer side
even though one was deleted successfully

## ✅ Expected Result
.The deleted file should not appear on either side(Privacy issue if sensitive files remain visible)

## 📎 Evidence (Screenshot/Video URI)
https://drive.google.com/file/d/1v0CXeIp-ER0LFZlVp0LUIWUWj4kJG598/view?usp=sharing

