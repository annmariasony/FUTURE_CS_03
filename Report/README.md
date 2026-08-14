# API Security Risk Analysis Report

## Future Interns – Cyber Security Task 3

This folder contains the final security assessment report prepared for **Future Interns Cyber Security Task 3 – API Security Risk Analysis**.

## Report

**File:** `Future_Interns_Task_3_API_Security_Risk_Analysis_Final.pdf`

The report documents a read-only security assessment of the public **JSONPlaceholder** test API.

## API Tested

**JSONPlaceholder**

https://jsonplaceholder.typicode.com/

The following endpoints were reviewed:

- `GET /posts`
- `GET /posts/1`
- `GET /users`
- `GET /users/1`

## Assessment Areas

The report covers:

- API endpoint analysis
- Authentication requirements
- Authorization considerations
- Response data exposure
- HTTP response headers
- Rate-limiting considerations
- Input validation considerations
- Risk severity classification
- Business impact
- Security recommendations

## Testing Methodology

Testing was performed using **Postman** with safe, read-only requests.

The assessment focused on identifying potential security risks without attempting exploitation, authentication bypass, denial-of-service testing, or unauthorized access.

## Risk Classification

Identified observations are classified as:

- **Low**
- **Medium**
- **High**
- **Informational**

The severity reflects the potential impact in a real-world production API environment.

## Evidence

Supporting screenshots are available in the repository's `Evidence/` directory.

## Ethical Scope

Only a publicly available test API was assessed.

No private or production systems were attacked, and no destructive or disruptive testing was performed.

## Conclusion

The report demonstrates a practical API security review process involving endpoint inspection, security risk identification, severity assessment, business impact analysis, and remediation recommendations.
