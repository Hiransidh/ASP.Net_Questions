# Cookies and Sessions - Questions

## One-Word Questions

1. What is the default expiration time for a session in ASP.NET? **20 minutes**  
2. Which method is used to remove a specific session? **`Session.Remove`**  
3. Which property of the `Response` object is used to create cookies? **`Cookies`**  
4. What is the default storage type for sessions? **`InProc`**  
5. Which attribute in the `web.config` file defines session state mode? **`mode`**  
6. What kind of cookie is deleted when the browser is closed? **Session cookie**  
7. Which ASP.NET object is used to manage user-specific data during a session? **`Session`**  
8. What is the name of the cookie used by default to track sessions? **`ASP.NET_SessionId`**  
9. Which class is used for creating cookies in ASP.NET? **`HttpCookie`**  
10. What is the default scope of a session variable? **Per user**  
11. Which method clears all session data? **`Session.Clear`**  
12. Which directive in the `web.config` file enables session state? **`<sessionState>`**  
13. How do you set the expiration of a cookie? **`Expires` property**  
14. Which object in ASP.NET stores user information in key-value pairs for the duration of the session? **`Session`**  
15. What property of a cookie makes it accessible only via HTTPS? **`Secure`**  
16. Which cookie property determines its availability across domains? **`Domain`**  
17. What session state mode stores data in a separate SQL Server? **`SQLServer`**  
18. Which object manages the lifecycle of cookies? **`HttpResponse`**  
19. What is the default storage location of session state in ASP.NET? **Memory**  
20. Which cookie property specifies the root directory for access? **`Path`**

---

## MCQs

### Cookies

1. **Which property is used to assign a value to a cookie?**  
   - a) Value  
   - b) Content  
   - c) Key  
   - d) Data  
   **Correct: a**

2. **What happens if a cookie is set without an expiration date?**  
   - a) It lasts for a week  
   - b) It is a session cookie  
   - c) It is persistent  
   - d) It is deleted immediately  
   **Correct: b**

3. **Which property of a cookie determines the expiration date?**  
   - a) Expires  
   - b) TimeOut  
   - c) Duration  
   - d) EndTime  
   **Correct: a**

4. **What is the maximum size of a cookie?**  
   - a) 2 KB  
   - b) 4 KB  
   - c) 8 KB  
   - d) 16 KB  
   **Correct: b**

5. **What is the key disadvantage of cookies?**  
   - a) Cannot store large data  
   - b) Can be easily intercepted  
   - c) Expensive to create  
   - d) Hard to manage  
   **Correct: b**

---

### Sessions

6. **What is the default session state mode in ASP.NET?**  
   - a) Off  
   - b) InProc  
   - c) StateServer  
   - d) SQLServer  
   **Correct: b**

7. **Which method is used to abandon a session?**  
   - a) Session.Dispose()  
   - b) Session.End()  
   - c) Session.Abandon()  
   - d) Session.Clear()  
   **Correct: c**

8. **Which object stores the session ID on the client side?**  
   - a) Cookie  
   - b) Session  
   - c) QueryString  
   - d) ViewState  
   **Correct: a**

9. **What happens if a session expires?**  
   - a) The session data is retained  
   - b) A new session is created  
   - c) An error is thrown  
   - d) The user is logged out  
   **Correct: b**

10. **Which property of a session specifies the timeout duration?**  
    - a) Timeout  
    - b) Duration  
    - c) Expires  
    - d) ExpirationTime  
    **Correct: a**

---

### Cookie and Session Differences

11. **Which data is stored on the client side?**  
    - a) Session  
    - b) Cookies  
    - c) ViewState  
    - d) Both b and c  
    **Correct: d**

12. **Which of the following can store larger data securely?**  
    - a) Cookies  
    - b) Session  
    - c) Both a and b  
    - d) Neither a nor b  
    **Correct: b**

13. **What happens if a user disables cookies in their browser?**  
    - a) Sessions will not work  
    - b) Sessions will use URL rewriting  
    - c) Sessions expire immediately  
    - d) Sessions throw an error  
    **Correct: b**

---

### Session Modes

14. **Which session mode stores session data in memory of the web server?**  
    - a) InProc  
    - b) StateServer  
    - c) SQLServer  
    - d) Custom  
    **Correct: a**

15. **Which session state mode is the most secure?**  
    - a) InProc  
    - b) StateServer  
    - c) SQLServer  
    - d) Off  
    **Correct: c**

16. **Which session mode is the fastest?**  
    - a) InProc  
    - b) StateServer  
    - c) SQLServer  
    - d) Custom  
    **Correct: a**

17. **Which session mode supports web farm scenarios?**  
    - a) InProc  
    - b) StateServer  
    - c) SQLServer  
    - d) Both b and c  
    **Correct: d**

18. **Which configuration in `web.config` turns off session state?**  
    - a) `<sessionState mode="None" />`  
    - b) `<sessionState mode="Off" />`  
    - c) `<sessionState enabled="false" />`  
    - d) `<sessionState disabled="true" />`  
    **Correct: a**

---

### Miscellaneous

19. **How can you share session state between multiple applications?**  
    - a) By using InProc  
    - b) By using SQLServer  
    - c) By using ViewState  
    - d) By using FileStorage  
    **Correct: b**

20. **Which object is used for storing temporary data across pages?**  
    - a) Cookies  
    - b) Session  
    - c) TempData  
    - d) Cache  
    **Correct: b**

21. **Which class is used to manipulate HTTP cookies?**  
    - a) CookieManager  
    - b) HttpCookie  
    - c) HttpCookieManager  
    - d) CookieHandler  
    **Correct: b**

22. **How do you make a session variable available across multiple requests?**  
    - a) By setting it in `ViewState`  
    - b) By storing it in `Session`  
    - c) By adding it to `Cookies`  
    - d) By writing it to `Response`  
    **Correct: b**

23. **Which ASP.NET feature allows state to persist without using cookies?**  
    - a) Session  
    - b) URL rewriting  
    - c) Cache  
    - d) Application state  
    **Correct: b**
