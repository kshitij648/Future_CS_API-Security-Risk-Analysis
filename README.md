# API Security Risk Analysis 🔐

## Internship
Future Interns – Cyber Security Task 3 (2026)

## Author
Kshitij Pandey

---

# Project Overview
This project performs an **API Security Risk Analysis** on a public test API to identify common security vulnerabilities such as authentication issues, excessive data exposure, and missing security protections.

The analysis was conducted using **Python and Jupyter Notebook**.

---

# Tested API
JSONPlaceholder Demo API  
https://jsonplaceholder.typicode.com

---

# Tools Used
- Jupyter Notebook
- Python (Requests Library)
- Kali Linux
- GitHub

---

# Methodology

The following steps were used during the analysis:

1. API endpoint testing  
2. Authentication analysis  
3. Header inspection  
4. Data exposure testing  
5. Object level authorization testing  

---

# Security Findings

1. **Unauthenticated API Access**  
   API endpoints can be accessed without authentication.

2. **Excessive Data Exposure**  
   API responses contain unnecessary user information.

3. **Broken Object Level Authorization**  
   Users can access different records by modifying the ID.

4. **Missing Rate Limiting**  
   No protection against API request flooding.

5. **Missing Security Headers**  
   Important security headers are not implemented.

---

# Conclusion
The API allows open access to multiple endpoints and lacks proper authentication and security
