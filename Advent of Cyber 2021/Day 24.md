## Challenge Name: Learning From The Grinch
### Topic: Post Exploitation
### Learning Objectives:
In this task you will:

-   Understand post exploitation
-   Understand how passwords are stored on Windows
-   Dump passwords from LSASS process on Windows
-   Crack Password Hashes

John command: `john --format=NT --wordlist=/usr/share/wordlists/rockyou.txt hash.txt --pot=output.txt`  
### Questions:
1. What is the username of the other user on the system?  
answer: `emily`   
found using mimikatz and listing password hashes.  
2. What is the NTLM hash of this user?  
answer: `8af326aa4850225b75c592d4ce19ccf5`   
3. What is the password for this user?  
answer: `1234567890`   