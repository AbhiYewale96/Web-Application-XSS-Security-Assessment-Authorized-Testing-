# 🔐 Web Application XSS Security Assessment

## 📌 Overview
Performed XSS vulnerability testing on a live web application in an authorized environment.

## 🛠 Tools Used
- Browser DevTools  
- Manual Testing  

## 🔍 Testing Performed
- Reflected XSS  
- Stored XSS  
- DOM-Based XSS

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
No XSS vulnerabilities were identified. The application demonstrated secure input validation.

## 📚 Key Learning
Understanding how real-world applications prevent XSS attacks using proper validation and encoding.

## ⚖️ Ethical Note
Testing was conducted with proper permission and followed ethical security practices.
