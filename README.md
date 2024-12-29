Name: Sangani Dhruvin

Study: B.tech in cyber security [UG]

College and: silver oak university

Intern company: CODTECHITSOLUTIONS

Task: CODTECH-Internship-web app pentesting.

The following testing techniques are performed to identify common vulnerabilities:

**SQL Injection**

SQL Injection (SQLi) allows attackers to execute arbitrary SQL code through input fields. If the web application does not properly sanitize user input, attackers can manipulate the database to gain unauthorized access, retrieve sensitive data, or perform other malicious actions.

Testing:
Inject common payloads into form fields or URL parameters.
Use automated tools like SQLmap to identify and exploit SQL injection vulnerabilities.

**Cross-Site Scripting (XSS)**

XSS allows attackers to inject malicious JavaScript code into web pages that are viewed by other users. This can lead to stolen credentials, session hijacking, and other malicious activities.

Testing:
Inject common XSS payloads like <script>alert('XSS')</script> into input fields or URL parameters.
Check if the input is reflected back to the page without proper sanitization.
Test for Reflected, Stored, and DOM-based XSS vulnerabilities.

**Brute force using burp suit**

in this attack we use an burpsuit tool for brutr force to guessing passwords.
open burpsuit.
set proxy.
send request to the interceptor.
send request to intruder and start attack using payloads and you got code 200 that is your password for login.
