---
layout: post
title: Secure Software Development 
subtitle: Discussion 1
categories: Unit 1
tags: [discusion, unit]
---
## Secure Software Development Module - Discussion 1
<H2>Unit 1 Collaborative Discussion :UML Flow Chart </H2>

[docs]: https://sudeshnaidoo.github.io/assets/pdf/uml-SD_unit1.pdf
Please find our assignment here -> [here][docs]

<p>The coding weakness that I have chosen from OWASP is Sql injection. This is a common attack and still prevalent today (Aradhya, D. 2017). The Sequential diagram (SD) was chosen as the flow of query and response can be seen. The SD shows two possible methods that can be used in a SQL injection attack ( Everatt, J. 2023). One type of attack in which a query is sent via the input field on the application and based on the response received or not received. The error response might give away backend information of the system. Even if no response is received it can then be inferred based on what was responded to and what was not. This allows the attacker to get one piece of data at a time (PortSwigger. n.d.).</p>
<p>The second attack is an Insufficient input data attack, which is also part of the SQL injection methodology of attacks. In this attack data is not sanitized or check and an attacker can input unexpected or malicious data and by pass security checks allowing the attacker to manipulate code or execute code (OWASP. n.d.).</p>
<p>I think the sequential diagram can also indicate why these attack vectors where possible was due to lack of test cases.</p> 


<H3>Reference:</H3>

  <p>Everatt, J. (2023). The Root of All E-vulns – MWR CyberSec. MWR CyberSec. https://www.mwrcybersec.com/the-root-of-all-e-vulns#:~:text=“The%20three%20root%20causes%20of,and%20the%20insufficient%20input%20validation. 

Aradhya, D. (2017). The root cause of an SQL injection attack and why it continues to be one of the most common security risks to a data server – Divya Aradhya. Divya Aradhya – Information Security. http://www.divyaaradhya.com/2017/04/27/the-root-cause-of-an-sql-injection-attack-and-why-it-continues-to-be-one-of-the-most-common-security-risks-to-a-data-server/ 

PortSwigger. (n.d.). What is Blind SQL Injection? Tutorial & Examples | Web Security Academy. Web Application Security, Testing, & Scanning - PortSwigger. https://portswigger.net/web-security/sql-injection/blind 

OWASP. (n.d.). M4: Insufficient Input/Output Validation | OWASP Foundation. OWASP Foundation, the Open Source Foundation for Application Security | OWASP Foundation. https://owasp.org/www-project-mobile-top-10/2023-risks/m4-insufficient-input-output-validation 
</p>
