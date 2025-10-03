# API Test Automation
Fast, reliable testing using Python and Pytest
###
API - Application Programming Interface (The Gateway to a system)
A browser is a fancy API requester. API is a gateway to the system.
<img width="1136" height="298" alt="browserAPI" src="https://github.com/user-attachments/assets/a7254c54-36c9-4158-a4a7-ba55828d0001" />

**API is valuable:**
- faster than tests using browser automation
- much faster
- Seriously, like 80% faster
  - no startup time for browser
  - no logging in via the browser for every single test case
  - no waiting for large element(like images) to downloadand display
  - no waiting on CSS to render
  - no waiting on JavaScript calls
- less brittle than browser automation
  - doesn't break if elements on a page move or change
  - Exercises the minimum code to test the component

|                             Browser                    |        API       |
| ------------------------------------------------------ | ---------------- |
|  UI behavior                                           | Everything else  |
| Validate dynamic context                               |                  |
| test suite that wastes a lot of time and breaks often  |                  |

**Test case strategies:**
- Browser and mobile automation is for User experience
- API test is for API contracts
- Unit Test is for all the functions and things that are not exposed by the API, but we still want them to work
  <img width="936" height="508" alt="unittest" src="https://github.com/user-attachments/assets/ebc0e797-5107-4eb5-9283-2228777f7bcd" />

  ***4 Things to remember:***
  <details>
    <summary>Click to expand for more details</summary>
    1. API testing is faster than browser automation
    2. When you see "API" think "A gateway to System."
    3. If it is not exposed by the API, you can't test it
    4. If you need to validate UI behavior or dynamically loaded data, use browser automation instead
  </details>

  **The HTTP Request**
  - Request Methods:
    - GET:  Postcard(URL only) 
    - POST: Can contain data (Letter or package)
    - DELETE: resource need to remove but need to have authentication

How to talke to web servers:
  1. Send request
  2. Receive response
  3. Check status

Was the request successful?
4xx - authendication not correct or you don't have your request formatted properly,
5xx - you broken the server (or The bug in the server)

|     2XX    |            4XX(cients)             |        5XX(Servers)            |
|------------|------------------------------------|--------------------------------|
|   Success! |Something is wrong with your request| The server encountered an error|

  ***3 Things to remember:***
  <details>
    <summary>Click to expand for more details</summary>
    1. Browsers are just fancy HTTP Requesters
    2. GET, POST, AND DELETE are the three most common Request Methods
    3. Each response contains a status code
  </details>

###


  

  

  
