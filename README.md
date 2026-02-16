# EemmanuelTitan-Task-3---FUTURE_CS_03
# API Security Risk Analysis – JSONPlaceholder

## API Tested
Public test API: [JSONPlaceholder](https://jsonplaceholder.typicode.com)

## Tools Used
- Postman (API testing)
- JSONPlaceholder (Public API for testing)
- MS words
- Screenshot tool for capturing requests/responses

## Scope
- Analyze endpoints for security weaknesses
- Read-only requests (GET)
- Ethical and non-intrusive testing

## Methodology
1. Selected `/users` endpoint for analysis
2. Inspected request and response in Postman
3. Checked authentication, authorization, data exposure, and rate limiting
4. Documented findings and remediation steps

## Key Findings
- Open endpoint with no authentication
- Excessive data exposure (full user details)
- Missing authorization checks
- No rate limiting detected

## Risk Severity
- High: Open endpoints, missing authorization
- Medium: Excessive data exposure, no rate limiting

## Remediation Recommendations
1. Add authentication (JWT/OAuth2)
2. Implement authorization (RBAC)
3. Return only necessary fields
4. Apply rate limiting

## Screenshots
See `screenshots/` in other file

