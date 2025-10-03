# API Test Automation
Fast, reliable testing using Python and Pytest
###
API - Application Programming Interface (The Gateway to a system)
A browser is a fancy API requester. API is a gateway to the system.
<img width="1136" height="298" alt="browserAPI" src="https://github.com/user-attachments/assets/a7254c54-36c9-4158-a4a7-ba55828d0001" />

*API is valuable:*
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

*Test case strategies:*
User experience - browser and mobile automation
API contracts - API test
all the functions and things that are not exposed by the API, but we still want them to work. -Unit Test
  <img width="936" height="508" alt="unittest" src="https://github.com/user-attachments/assets/ebc0e797-5107-4eb5-9283-2228777f7bcd" />

  

  

  
