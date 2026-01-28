 Markdown
 # RESTful API Activity - [John Lorimer Imperio]
 ## Best Practices Implementation
 1. Environment Variables:
 - Why did we put `BASE_URI` in `.env` instead of hardcoding it?
 - Answer: Because it helps the application become more flexible and secure. It allows us to change API versions or deployment settings without modifying the source code

 2. Resource Modeling:
 - Why did we use plural nouns (e.g., `/dishes`) for our routes?
 - Answer: because it gives consistency

 3. Status Codes:
  - When do we use `201 Created` vs `200 OK`?
  - Why is it important to return `404` instead of just an empty array or a generic error?
  - Answer: 201 is created if there was a new thing made in POST while 200 ok is used for Get, PUT, or DELETE requests

 4. Testing:
 - <img width="1365" height="708" alt="image" src="https://github.com/user-attachments/assets/8bbb1891-7179-4b32-b115-3dbcb1f67fa1" />
