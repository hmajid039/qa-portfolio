# TC-BYN-002 – When a user changes the language from the dropdown on the login popup, the syste

**Reported By:** Majid Ali  
**Environment:** Staging  
**Device:** N/A  
**Date:** 2025-10-06 00:00:00  
**Status:** The reasons are provided by Phu quoted by Asif in a group - Reasons why a page reload might occur or be implemented:
-Framework-specific routing: In frameworks like Next.js, changing the locale might be tied to the routing system, which often involves a page reload or navigation to a new URL with the updated locale in the path. This can be the simplest way to ensure all components and data are re-rendered with the new language.
- Data fetching and server-side rendering (SSR): If your application relies on server-side rendering or fetches data based on the current language (e.g., from a CMS or API), a page reload ensures that the server can provide the correct content for the new language. This is particularly relevant for content that isn't purely static strings.
- Must reload page to change language on maps  
**Severity:** N/A  
**Priority:** N/A  

---

## 🐞 Description
When a user changes the language from the dropdown on the login popup, the system redirects to the homepage instead of updating the login page content in the selected language.

## 🔁 Steps to Reproduce
N/A

## ❌ Actual Result
The system redirects to the homepage with the selected language instead of keeping the user on the login page.

## ✅ Expected Result
The user should remain on the login page, and only the language of the page content should change accordingly.

## 🔗 URL
N/A
