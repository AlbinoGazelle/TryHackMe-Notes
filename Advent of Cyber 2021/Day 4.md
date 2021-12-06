## Topic: Web Exploitation
### Challenge Name: Santa's Running Behind

Given a login portal, use supplied passwords to bruteforce page.
Use burp suite "battering ram" with login request to bruteforce:
![[Pasted image 20211204120411.png]]
Request with the password "cookie" is a different length, means we have the password.
Login with username "santa" password "cookie" to get flag
