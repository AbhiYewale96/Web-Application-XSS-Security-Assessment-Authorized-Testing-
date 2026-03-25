# 🔐 Web Application XSS Security Assessment

## 📌 Overview
This project demonstrates a professional security assessment performed on a live web application to identify Cross-Site Scripting (XSS) vulnerabilities. The testing was conducted in an authorized environment following ethical security practices.

## 🎯 Objective
To evaluate the application's resilience against:

Reflected XSS

Stored XSS

DOM-Based XSS

## 📍 Scope
Target: Live Web Application (Authorized Testing)

Module Tested: Contact Form

Input Fields:

Full Name

Email Address

hone Number

Message Field

## 🛠 Tools Used
Web Browser (Google Chrome)

Browser Developer Tools

Manual Payload Testing

## 🔍 Testing Methodology
The assessment followed a structured approach:

Input Field Identification

Payload Injection

Response Analysis

Execution Validation

## ⚠️ Payloads Used
<script>alert(1)</script>

<img src=x onerror=alert(1)>

<script>alert('stored')</script>

## 📸 Screenshots

## Identfied Fields
![Identified Fields](screenshots/Identified%20fields.png)
This screenshot shows all user input fields discovered during testing.

## Payload1 Test
![Payload1 Test](screenshots/Payload1(Reflected%20XSS).png)
Payload entered in Name and Message fields.

## Payload1 Submitted
![Payload1 Submitted](screenshots/Payload1%20submitted.png)
No popup was observed. Input was not executed.

## Payload2 Test
![Payload2 Test](screenshots/Payload2(Reflected%20XSS).png)
Payload entered in Name and Message fields.


## Payload2 Submitted
![Payload2 Submitted](screenshots/Payload2%20submitted.png)
No popup was observed. Input was not executed.

## Stored XSS
![Stored XSS Test](screenshots/Stored%20XSS%20payload.png)

## Stored XSS Submitted
![Stored XSS Submitted](screenshots/Stored%20payload%20submitted.png)

## NO Execution
![No Execution](screenshots/No%20execution(Stored%20XSS).png)
Input may be stored but not executed. No stored XSS found.

## DOM XSS
![DOM XSS](screenshots/DOM%20XSS.png)
No execution observed.

## Source Page
![Source Page](screenshots/Source%20page.png)

## 📊 Result
Test Type	Result

 Reflected XSS -	Not Vulnerable
 
 Stored XSS -	Not Vulnerable
 
 DOM-Based XSS -	Not Vulnerable

 ## 🔎 Observations
Input validation is properly implemented
Script payloads are not executed
No reflection of malicious input in response
Application demonstrates secure input handling

## ✅ Conclusion
The application is not vulnerable to basic XSS attacks in the tested scope. Proper validation and secure coding practices effectively prevent script execution.

## 🛡 Recommendations
Implement output encoding
Apply strict input validation
Use Content Security Policy (CSP)
Conduct regular security testing

## 📚 Learning Outcome
This project provided hands-on experience in testing real-world applications and understanding how modern applications defend against XSS attacks.

## ⚖️ Ethical Consideration
This assessment was conducted with proper authorization. No harmful or intrusive actions were performed.

## 🔗 Author
Abhishek Yewale
Cybersecurity Enthusiast | VAPT | OWASP Top 10
