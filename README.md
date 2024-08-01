# Tricentis-qTest
[qTest](https://www.tricentis.com/products/unified-test-management-qtest) is enterprise test management platform from [Tricentis](https://www.tricentis.com)

qTest also provides a very robust rest API. Enterprise customer may utilize it to their best use.

Tricentis has published white papers on it's approach and strategy to help customer move to Tricentis products. 
e.g [quality-center-migration-guide](https://www.tricentis.com/resources/quality-center-migration-guide)

## IRIExperts is exploring qTest API
We are running this initiative to study and explore what qTest API supports and what it does not.

This repository is just a public page and we would **not publish** source code at this stage, but may publish samples, snippets and our learnings on the journey in the Wiki section. Stay tuned.


### [Login to qTest API](https://qtest.dev.tricentis.com/#/login/postAccessToken)
The login API endpoint is used for authenticating users. It allows clients to send user credentials (such as username and password) to the server for verification.

### Request
- **Method:** POST
- **Endpoint:** `/login`
- **Headers:**
  - `Content-Type: application/json`
  - `Authorisation: base64 string of you instance name with a colon at the end`
- **Body:**
  ```json
  {
    "grant_type": "password"
    "username": "your_username",
    "password": "your_password"
  }

### Alternately you can grab your access token from the resources section of qTest and send it on each api call as the authorisation header.

### Request
- **Method:** based on the end point you are using
- **Endpoint:**  your endpoint
- **Headers:**
  - `Content-Type: application/json`
  - `Authorisation: Bearer <access token >`





