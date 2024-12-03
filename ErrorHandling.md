# Error Handling - Questions

## One-Word Questions

1. What is the base class for all exceptions in .NET? **`System.Exception`**  
2. Which block is used to handle exceptions? **`catch`**  
3. What block always executes, regardless of an exception? **`finally`**  
4. What keyword is used to manually throw an exception? **`throw`**  
5. Which exception occurs when dividing a number by zero? **`DivideByZeroException`**  
6. What is the default error page in ASP.NET? **`CustomError`**  
7. What type of exception is thrown for null references? **`NullReferenceException`**  
8. Which class is used to log errors in the Event Viewer? **`EventLog`**  
9. What HTTP status code is returned for "Page Not Found"? **`404`**  
10. What directive in ASP.NET is used to handle page-level errors? **`<error>`**  
11. What is the recommended way to display user-friendly error messages? **Custom error pages**  
12. Which object is used to log errors during runtime in ASP.NET? **`Trace`**  
13. Which method in the `Server` object clears the last error? **`ClearError`**  
14. What property provides information about the last exception? **`LastError`**  
15. Which event in the `Global.asax` file is used for application-level error handling? **`Application_Error`**  
16. Which exception is thrown for invalid array indices? **`IndexOutOfRangeException`**  
17. What exception is thrown when accessing a file that does not exist? **`FileNotFoundException`**  
18. What keyword is used to re-throw an exception in the same state? **`throw`**  
19. What class is used for logging unhandled exceptions in ASP.NET? **`HealthMonitoring`**  
20. What property contains the error message in an exception? **`Message`**

---

## MCQs

### Exception Basics

1. **What is the purpose of the `try` block?**  
   - a) Catch exceptions  
   - b) Throw exceptions  
   - c) Execute code that might throw exceptions  
   - d) Skip error-prone code  
   **Correct: c**

2. **Which block is mandatory in a try-catch-finally statement?**  
   - a) `try`  
   - b) `catch`  
   - c) `finally`  
   - d) None of the above  
   **Correct: a**

3. **What happens if an exception is not caught in a `try` block?**  
   - a) The application continues normally  
   - b) The application crashes  
   - c) The exception is ignored  
   - d) The application logs the error  
   **Correct: b**

4. **Which keyword allows you to re-throw the same exception?**  
   - a) throw  
   - b) rethrow  
   - c) retry  
   - d) catch  
   **Correct: a**

5. **Which exception is thrown when a method is called on a null object reference?**  
   - a) ArgumentException  
   - b) NullReferenceException  
   - c) InvalidOperationException  
   - d) ObjectDisposedException  
   **Correct: b**

---

### Advanced Exception Handling

6. **Which method in `Exception` class provides the stack trace?**  
   - a) `StackTrace`  
   - b) `TraceError`  
   - c) `GetTrace`  
   - d) `ErrorPath`  
   **Correct: a**

7. **What is the purpose of the `finally` block?**  
   - a) Catch unhandled exceptions  
   - b) Execute cleanup code  
   - c) Skip the exception block  
   - d) Log the exception  
   **Correct: b**

8. **What happens when `throw` is used without specifying an exception?**  
   - a) A new exception is thrown  
   - b) The previous exception is re-thrown  
   - c) The exception is suppressed  
   - d) The application exits  
   **Correct: b**

9. **Which type of exceptions should be caught first in a multi-catch block?**  
   - a) Generic exceptions  
   - b) Specific exceptions  
   - c) Logical exceptions  
   - d) Application exceptions  
   **Correct: b**

10. **What is the purpose of the `InnerException` property?**  
    - a) To provide error message  
    - b) To log the exception  
    - c) To capture nested exceptions  
    - d) To override exception data  
    **Correct: c**

---

### Error Handling in ASP.NET

11. **What is the purpose of the `CustomErrors` section in `web.config`?**  
    - a) To disable error handling  
    - b) To specify error pages  
    - c) To ignore exceptions  
    - d) To log errors automatically  
    **Correct: b**

12. **What event is triggered for application-level exceptions?**  
    - a) `Page_Error`  
    - b) `Global_Error`  
    - c) `Application_Error`  
    - d) `Exception_Error`  
    **Correct: c**

13. **Which method is used to log errors in ASP.NET?**  
    - a) `WriteLog`  
    - b) `LogError`  
    - c) `Trace.Write`  
    - d) `Trace.Warn`  
    **Correct: d**

14. **Which object is used to redirect users to a custom error page?**  
    - a) `HttpContext`  
    - b) `Response.Redirect`  
    - c) `Server.Transfer`  
    - d) Both b and c  
    **Correct: d**

15. **Which directive can enable debugging for an ASP.NET application?**  
    - a) `<compilation debug="true" />`  
    - b) `<debug enabled="true" />`  
    - c) `<error debug="true" />`  
    - d) `<appSettings debug="true" />`  
    **Correct: a**

---

### Common Exceptions

16. **What exception is thrown when accessing an out-of-range index in an array?**  
    - a) InvalidCastException  
    - b) IndexOutOfRangeException  
    - c) ArgumentOutOfRangeException  
    - d) NullReferenceException  
    **Correct: b**

17. **Which exception is thrown for invalid type casting?**  
    - a) InvalidCastException  
    - b) ArgumentException  
    - c) TypeMismatchException  
    - d) DataTypeException  
    **Correct: a**

18. **What exception is thrown when a file operation fails due to permissions?**  
    - a) UnauthorizedAccessException  
    - b) FileNotFoundException  
    - c) IOException  
    - d) AccessDeniedException  
    **Correct: a**

19. **Which exception is thrown when a required argument is not provided?**  
    - a) ArgumentException  
    - b) ArgumentNullException  
    - c) MissingArgumentException  
    - d) ArgumentMissingException  
    **Correct: b**

20. **What is the exception type for arithmetic overflow?**  
    - a) OverflowException  
    - b) ArithmeticException  
    - c) DivideByZeroException  
    - d) MathException  
    **Correct: a**

---

## Practical Questions

1. Write a program that demonstrates how to use `try-catch-finally` to handle a `DivideByZeroException`.
2. Create a custom exception class named `InvalidAgeException` and demonstrate its usage.
3. Implement a program to log errors in the Windows Event Viewer.
4. Write a program to demonstrate the `InnerException` property.
5. Develop an ASP.NET application with custom error pages defined in `web.config`.
6. Write a program that uses `Application_Error` in the `Global.asax` file to handle unhandled exceptions.
7. Demonstrate the use of `throw` and `throw ex` in exception handling.
8. Write a program to handle a `NullReferenceException` and provide a fallback value.
9. Create a program to simulate and handle a `FileNotFoundException`.
10. Demonstrate how to use `Response.Redirect` to redirect to a custom error page in ASP.NET.

---

## Open-Ended Questions

1. What are the benefits of using `finally` in error handling?  
2. Explain the difference between `throw` and `throw ex`.  
3. What are the best practices for implementing custom error pages?  
4. How can you log errors in a production ASP.NET application?  
5. Why is exception handling important in web applications?  
6. What is the difference between system exceptions and application exceptions?  
7. How can you ensure thread safety in error handling?  
8. Discuss how `Application_Error` can be used for centralized error handling.  
9. What is the impact of enabling debug mode in `web.config`?  
10. How would you handle exceptions in a web farm or distributed environment?  
