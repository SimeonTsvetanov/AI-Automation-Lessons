# Data from outside your business

## Main Topics

1. **What is an API?** - Application Programming Interface - a way for different software to communicate
2. **When would I need one?** - When you need to get data from external services or systems
3. **Getting data for your business** - Using APIs to fetch information from third-party sources
4. **Connect to ANY data source in <2 min** - Quick integration with external data providers

---

There are different HTTP methods (commands) to communicate with APIs:

**GET** - Retrieve/Read data from a server

- Used to fetch information (e.g., getting user profile, product list)
- Data is sent in URL parameters
- Safe and idempotent (can be called multiple times without side effects)

**POST** - Create new data on the server

- Used to submit new information (e.g., creating user account, submitting form)
- Data is sent in request body
- Not idempotent (calling multiple times may create duplicate resources)

**PUT** - Update/Replace entire resource

- Used to completely replace an existing resource
- Requires all fields to be provided
- Idempotent (calling multiple times has same effect)

**PATCH** - Partially update a resource

- Used to modify specific fields of an existing resource
- Only sends the fields that need to be changed
- More efficient than PUT for partial updates

**DELETE** - Remove data from server

- Used to delete existing resources
- Idempotent (calling multiple times has same effect)
- Should be used carefully as it permanently removes data

**Additional HTTP Methods:**

- **HEAD** - Get response headers only (no body)
- **OPTIONS** - Get information about communication options
- **TRACE** - Diagnostic method for debugging

---


## HTTP Status Codes

**2xx Success Codes:**

- **200 OK** - Request successful, data returned as expected
- **201 Created** - New resource successfully created
- **204 No Content** - Request successful but no data to return

**3xx Redirection Codes:**

- **301 Moved Permanently** - Resource has been permanently moved
- **302 Found** - Resource temporarily moved
- **304 Not Modified** - Cached version is still valid

**4xx Client Error Codes:**

- **400 Bad Request** - Invalid request format or parameters
- **401 Unauthorized** - Authentication required
- **403 Forbidden** - Access denied (authenticated but not authorized)
- **404 Not Found** - Requested resource doesn't exist
- **429 Too Many Requests** - Rate limit exceeded

**5xx Server Error Codes:**

- **500 Internal Server Error** - Server encountered an error
- **502 Bad Gateway** - Server received invalid response from upstream
- **503 Service Unavailable** - Server temporarily unavailable
- **504 Gateway Timeout** - Server timeout while waiting for upstream

**Common API Response Patterns:**

- **Success**: 200-299 status codes with requested data
- **Error**: 4xx-5xx status codes with error message/details
- **Rate Limiting**: 429 status when too many requests made
- **Authentication**: 401/403 when credentials missing or invalid

---

## Project: External API Integration Workflow

### Project Description

Replace the existing email PDF extraction workflow with external API integration to extract data from emails/PDFs and populate our database.

### Project Goals

- [ ] Integrate external API for PDF/text extraction
- [ ] Replace manual email processing with automated API calls
- [ ] Streamline data extraction and database population
- [ ] Improve accuracy and speed of data processing

### Implementation Steps

- [x] Step 1: Add HTTP Request node
  - set the note to POST
  - using Generic Auth Type
  - and as per API docs we have to use Header Auth (name: x-api-key, value: authcode)

### Notes and Observations

- [To be filled during implementation]

### Challenges Encountered

- [To be filled if any issues arise]

### Resources Used

- [pdf.co](https://pdf.co/)

---