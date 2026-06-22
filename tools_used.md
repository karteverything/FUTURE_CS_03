## Tools Used
This document outlines the tools used during the API Security Risk Analysis
conducted as part of the Future Interns Cyber Security Internship Task 3.

### Assessment Objective
The objective of this assessment was to analyze a public API, identify common
API security risks, evaluate authentication and data exposure practices, and
provide recommendations based on secure API development principles. 

### Target API
API: JSONPlaceholder  
Base URL:  
https://jsonplaceholder.typicode.com  

JSONPlaceholder is a publicly available REST API designed for testing and 
learning purposes. 

### Tools Overview
| Tool | Purpose |
|------|---------|
| Postman | API testing and response inspection |
| Browser | Documentation review and endpoint verification |
| JSONPlaceholder Documentaion | API reference and endpoint information |
| Microsoft Word | Report creation and documentation |

### Assessment Activities
API Document Review
- Reviewed API structure and available endpoints.
- Identified publicly accessible resources.

Endpoint Testing
- Send GET requests to API endpoints.
- Observed reponse behaviour and returned data.

Header Analysis
- Inspected HTTP response headers.
- Reviewed available security-related information.

Response Analysis
- Examined returned data for potential overexposure.
- Review user information and resource accessibility.

Risk Assessment
- Classified identified risks according to severity.
- Assessed potential business impact.


### Key Findings
- Open public endpoints accessible without authentication.
- Excessive exposure of user-related information.
- Lack of authentication controls.
- No visible rate-limiting indicators observed.

### Conclusion
The tools used during this assessment provided valuable insight into API security 
concepts, including authentication, access control, data exposure, and API abuse
prevention. The findings demonstrate common risks organizations should consider when
developing and securing modern APIs. 
