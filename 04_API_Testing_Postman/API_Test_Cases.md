# API Testing Scenarios

I used **Postman** to validate the backend services. Testing APIs ensures that the data being sent to the UI is correct and secure.

### 1. Product Search API (GET)
- **Endpoint:** `/api/v1/products/search?name=laptop`
- **Validation:** - Verified Status Code is `200 OK`.
  - Validated that the response is in **JSON** format.
  - Checked that the 'Price' field is not empty for any product.

### 2. User Authentication (POST)
- **Endpoint:** `/api/v1/auth/login`
- **Validation:**
  - Verified `200 OK` for valid credentials.
  - Verified `401 Unauthorized` for wrong passwords (Negative Testing).
  - Checked if a **Bearer Token** is returned for secure sessions.

### 3. Cart Management (POST/DELETE)
- **Endpoint:** `/api/v1/cart/add`
- **Validation:**
  - Verified `201 Created` when a new item is added.
  - Verified that the 'Cart Total' updates correctly in the response body.

###  Tools Used
- **Postman** (for sending requests).
- **JSON** (for data validation).
