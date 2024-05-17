---
layout: post
title: Secure Software Development- Discussion 1 -Semianr 2
subtitle: Secure Software Development
categories: Seminar
tags: [discussion, unit]
---


##Secure code discussion: Seminar 2

<p>As per (PDF) - no language is secure
-code vulnerabilities are written inadvertently
-	Buffer errors caused due to manual management ( allocation, reallocation and deallocation) of pointers
-	Injection errors are caused because code is represented as strings, use of string concatenation, and sanitation of strings.
-	Information leak errors - due to manual tracking of sensitive data, ensuring data is not leaked to to less sensitive objects.
-	Cognitive load - abstraction - use of code that manages memory allocation and deallocation.
-	use of RAII -resource acquisition is initialization -  allows only one owner per resource.
-	Borrowing is an abstraction - allows a resource to be shared in a secure way. Shared borrow - the shared reference can not be mutated. Mutual borrow - the shared reference cannot be aliased  but not at the same time. -  used for memory safety.</p>
<p>LINQ - language Intergrated Query solve class declaration - object-relational mapping framework that automatically generates strongly typed .NET
class declarations that correspond to tables in the database. LINQ-to-SQL also solves the
SQL injection problem because the programmer no longer constructs SQL code using strings
and string concatenation (the source of SQL injection errors) but uses the language-level
-	queries, which themselves pass all data to the database using injection-safe SQL parameters</p>


<p>Reference:</p>
<p>Cifuentes, C. & Bierman, G. (2019) What is a Secure Programming Language? 3rd Summit on Advances in Programming Languages (SNAPL).136(3): 1 - 15. 
</p>
