## FUTURE_CS_03: API Security Risk Analysis Report - Future Interns Cyber Security Task 3

### Intern Information
Intern: Mlungisi Sibitane  
Organization: Future Interns

### Objective
The objective of this project was to perform a security-focused review of a public API, identify common API security risks, assess potential business impact, and provide practical remediation recommendations. 

### Target API
JSONPlaceholder: https://jsonplaceholder.typicode.com

### Deliverables
- API Security Risk Analysis Report (pdf)
- Evidence Screenshots
- Tools Documentation

### Tools Used
- Postman
- Chrome Web Browser
- JSONPlaceholder Documentation
- Microsoft Word

### Findings Summary
| ID | Finding | Risk Level |
|----|---------|------------|
| F-01 | Open Public Endpoints | Medium |
| F-02 | Excessive Data Exposure | Medium |
| F-03 | Missing Authentication Control | Medium |
| F-04 | Missing Rate Limiting Indicators | Low |

### Key Findings
- Identified publicly accessible API resources without authentication requirements.
- Observed exposure of user-related information through API responses.
- Evaluated the absence of authentication mechanisms.
- Reviewed reponse headers for security-related controls.
- Assessed potential risks associated with API abuse and information disclosure.

### Overall Risk Rating
- Medium
While JSONPlaceholder is intentionally designed as a public testing API, similar configurations in production environments could increase the risk of unauthorized access, information disclosure, and API abuse.

### Recommendations
- Implement authentication controls such as OAuth2, JWT, or API Keys.
- Apply role-based access control (RBAC).
- Minimize exposed data fields.
- Implement API rate limiting.
- Conduct regualar API security assessments.

### Conclusion
This project successfully demonstrated the process of conducting an API Security Risk Analysis using a public testing API. Through endpoint testing, response analysis, and header inspection, several common API security considerations were identified, including open access to resources, excessive data exposure, missing authentication controls, and the absence of visible rate-limiting mechanisms.

Although the assessed API is intentionally designed for testing and learning purposes, the findings highlight security risks that organizations should address when developing and deploying production APIs. Implementing strong authentication, access controls, data minimization practices, and abuse prevention mechanisms can significantly improve API security.

Overall, this assessment provided valuable hands-on experience in API security analysis and reinforced the importance of secure API design in modern applications and SaaS environments.
