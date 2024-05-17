---
layout: post
title: Secure Software Development- Discussion 1 -Unit 2
subtitle: Secure Software Development
categories: Unit 
tags: [discussion, unit]
---

##SSD Discussion 1 -week 2 - Peer Responses 

<H2>Unit 1 - week 2 -discussion -peer response *2 </H2>

##Peer Response 1

<H>Hi Amrol</H>
<p>Your OWASP security risk, Insecure Design is very pertinent to the secure security design. If we look at CLASP OWASP secure design methodology(SecureSoftware. 2005) ,it tries to cover insecure coding. In terms of Insecure design for architecture we can use known architectural patterns as discussed in unit2 lecture cast. <p>
<p>Looking at your design flow chart  it clearly shows the user flow, but the vulnerability is difficult to workout from the diagram itself and the explanation is required to clarify. I would suggest a secondary actor input where you have a pointer to the vulnerability and possibly method of infiltration used to exploit the insecure design.</p>
<p>It is interesting to see in the scenario example you show how important it is for an external security   consultant with an external view point is, to an implementation or even security training and awareness for teams coding.</p>


<H3>Reference:</H3>
<p>SecureSoftware. (2005). https://cwe.mitre.org/documents/sources/TheCLASPApplicationSecurityProcess. CWE - Common Weakness Enumeration. https://cwe.mitre.org/documents/sources/TheCLASPApplicationSecurityProcess.pdf </p>



##Peer Response 2

<p>Hi Anja</p>
<p>Broken authentication is an interesting topic. The use case diagram clearly shows the attack vector and possible mitigations. Although in your discussion you mention the factors required for authentication but the diagram did not show second factor (2FA) as a mitigation option for authentication attack.</p>
<p>Even API’s are vulnerable to broken authentication attacks if:
•	 they allow weak passwords 
•	 permit brute force attacks from a list of valid usernames and password
•	doesn’t authenticate the validity of tokens or 
•	uses weak encryption etc...(OWASP. 2023)
 Some mitigation for API broken authentication is also noted as in your diagram is actually a flow diagram and mentioned mitigations.</p>

<H3>Reference: </H3>
<p>OWASP. (2023). API2:2023 Broken Authentication - OWASP API Security Top 10. OWASP Foundation, the Open Source Foundation for Application Security | OWASP Foundation. https://owasp.org/API-Security/editions/2023/en/0xa2-broken-authentication/ </p>

