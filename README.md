# Clarivate Derwent Sequence API

Derwent Sequence API provides seamless access to enriched sequence data, enabling users to enhance their research capabilities and make faster, more informed decisions.

## Table of Contents

- [Getting Started](#getting-started)
- [Base URL](#base-url)
- [Authentication](#authentication)
- [Error Handling](#error-handling)
- [Endpoints](#endpoints)
  - [Overview](#overview)
- [Support](#support)
- [Terms of service](#terms-of-service)

---

## Getting Started

### Register Developer Portal

1. Go to <a href="https://developer.clarivate.com/" target="_blank">Clarivate Developer Portal ↗</a> and select **Sign up** to open a new page page
2. Click **Register** to open the register page, following the instruction to input your ***email address***, ***password*** and other information, then click **Register**
3. You will receiven an email, follow the instruction to confirm the registration

### Register Application

1. Go to <a href="https://developer.clarivate.com/" target="_blank">Clarivate Developer Portal ↗</a> and select **Log in** to open a new page
2. Input your email address and password, and click **Sign in** to your personal home page
3. Click **Applications** in the menu to open the appication page
4. Click **Register a new Application** to show the panel, input the required fields (You can input a few words and update it later), click **Register Application**

### Subscribe Patent API

1. If you haven't subscribed any API, in your **Application** page, you can click **View APIs >>**. Alternatively, you can click **APIs** menu to naviage to APIs page
2. In the APIs page, find and click **Intellectual Property (IP) Data API** You can find it by searching the name in browser or use filter **Derwent** to narrow down the APIs list
3. In the **Intellectual Property (IP) Data API** page,scroll to the bottom, click **Subscribe** to raise the request
4. Please inform your account manager your email address, our approver will check your subscription request and approve

[⬆ Back to Top](#table-of-contents)

---

## Base URL

- https://api.clarivate.com

[⬆ Back to Top](#table-of-contents)

---

## Authentication

Use a bearer token in the Authorization header. Tokens are issued via your developer console.

| **Header**   | **Example**                          | **Description**                    |
|--------------|--------------------------------------|------------------------------------|
| Content-Type | application/json                     | All request bodies are JSON        |
| Accept       | application/json                     | All responses are JSON             |
| X-ApiKey     | 1e3f2b1c-9b0e-4b8a-9a6a-9f7d0a6b4a2f | Authorization key to make requests |

[⬆ Back to Top](#table-of-contents)

---

## Error Handling

- Responses uses the below json format

```json
{
  "code": 2100,
  "error": "Missing mandatory parameter(s): query"
}
```

Common status codes

- 200 OK

- 400 Bad Request

- 401 Unauthorized

- 403 Forbidden

- 404 Not Found

[⬆ Back to Top](#table-of-contents)

---

## Endpoints

This section describe the common concept for Sequence APIs

### Overview

Sequence API has three types of endpoints

| Type | Description |
|------|-------------|
| **Projects** | **Project management endpoints** |
|            | GET /reports |
| **Searches** | **Searches management endpoints** |
|            | GET /reports/\{report_id\}/searches |
| **Publications & Sequences** | **Publication basic and Sequence information endpoints** |
|            | GET /patents/\{patent_id\} |


[⬆ Back to Top](#table-of-contents)

---

## Support

Send [Email](mailto:Derwent.support@clarivate.com) to us if you have any feedback.

---

## Terms of service

Visit Clarivate <a href="https://clarivate.com/legal-center/terms-of-business/product-service-terms/" target="_blank">Terms of service ↗</a>

<p align="center"><a href="#table-of-contents">⬆ Back to Top</a></p>

---
