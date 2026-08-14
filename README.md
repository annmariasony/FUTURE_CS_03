# Cyber Security Task 3 – API Security Risk Analysis

## Overview

This repository contains the work completed for **Future Interns Cyber Security Task 3: API Security Risk Analysis**.

The objective of this task was to perform a read-only security assessment of a publicly available test API, identify common API security risks, assess their severity and business impact, and provide appropriate remediation recommendations.

## API Tested

**API:** JSONPlaceholder  
**URL:** https://jsonplaceholder.typicode.com/

JSONPlaceholder is a public fake REST API designed for testing and learning.

### Endpoints Reviewed

- `GET /posts`
- `GET /posts/1`
- `GET /users`
- `GET /users/1`

Testing was performed using **Postman** using read-only requests.

## Tools Used

- Postman – API requests and response inspection
- Browser – API documentation and endpoint verification
- GitHub – Documentation and evidence submission
- PDF – Security assessment report

## Scope

The assessment was limited to:

- Public/test API endpoints
- Read-only GET requests
- Request and response inspection
- HTTP headers
- Authentication requirements
- Response data exposure
- Basic authorization considerations

No exploitation, authentication bypass, flooding, denial-of-service testing, or attacks against private/production systems were performed.

## Methodology

The assessment followed these steps:

1. Selected a publicly available test API.
2. Reviewed the API structure and available endpoints.
3. Sent read-only requests using Postman.
4. Inspected request and response information.
5. Reviewed authentication and authorization requirements.
6. Checked the amount of data returned by endpoints.
7. Considered common API security risks.
8. Classified identified risks by severity.
9. Documented business impact and remediation recommendations.
10. Saved screenshots as supporting evidence.

## Key Security Observations

The assessment considered the following API security areas:

| Security Area | Observation | Severity |
|---|---|---|
| Authentication | Public endpoints do not require authentication | Low |
| Authorization | Public test API does not demonstrate user-level access control | Medium |
| Data Exposure | API responses expose structured user/post information | Low |
| Rate Limiting | No rate-limit protection was observed during basic testing | Medium |
| Input Validation | Read-only testing provided limited opportunity to assess input validation | Informational |

### Important Note

JSONPlaceholder is intentionally designed as a public testing API. Therefore, these observations should not automatically be treated as exploitable vulnerabilities in a production application.

They represent security considerations that should be addressed when implementing similar API functionality in a real SaaS or production environment.

## Evidence

Screenshots supporting the assessment are available in the `Evidence/` directory.

Evidence includes:

- `3S1.png` – Posts endpoint response
- `3S2.png` – Response headers
- `3S3.png` – Individual post endpoint
- `3S4.png` – Users endpoint
- `3S5.png` – Individual user endpoint

## Report

The complete API Security Risk Analysis report is available in:

`Report/Future_Interns_Task_3_API_Security_Risk_Analysis_Final.pdf`
