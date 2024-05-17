---
layout: post
title: Secure Software Development- Assignment 1
subtitle: Secure Software Development
categories: assignment
tags: [assignment, unit]
---

##SSD -Group3 Team project 
<H2> Variable Break Down</H2>

<p>Variables:</p>
<p>USER:</p>
<p>
Username	STR
Password	STR
UserID	INT
Salt	STR
Digital Signature	STR
</p>
<p>ADMIN:
Username	STR
Password	STR
AdminID	INT
Salt	STR
</p>
<H2>B-CRYPT TO STORE PASSWORDS</H2>

<p>MUSIC TABLE:
musicID	INT
musicName	STR
musicLyric	FILE?
musicScore	FILE?
musicRecord	FILE?
userID (Foreign Key)	INT
creationDate	Date
modDate	Date
checkSum	STR
</p>	

<H2>ENCRYPTION: HASHED WITH B-CRYPT</H2>
<p>musicID, musicName, musicLyric, musicScore and musicRecord is linked to userID.
All the elements of the above are linked to the checksum. </p>

<p>What does each user do?</p>
<p>USER:
OWN ARTIFACT	OTHER ARTIFACT
Add	View
Modify	
Delete	
View	
Check Integrity 	
Encrypt / Decrypt</p>	
	

<p>ADMIN
ALL ARTIFACTS
Add
Modify
Delete
View
Check Integrity 
Encrypt / Decrypt
View

</p>