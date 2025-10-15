The machine i solve form the first question so I will also mentined the answers of the question. 

1. What does the acronym SQL stand for? 
- Structured Query Language

2. What is the most common type of SQL vulnerabilities?
- SQL injection

3. What is the 2021 OWASP Top 10 classification for this vulnerability? 
- A03:2021-Injection

4. What does Nmap report as the service and version that are running on port 80 of the target? 
- Apache httpd 2.4.38 ((Debian)) 

to get till this ans we need to have to do some nmap scanning... i used nmap clasic command which is "nmap -sC -sV <Target-ip> -v" from this command i get the open ports and the services running on it as shown in following screenshot

<img width="449" height="36" alt="Appoitment nmap scan" src="https://github.com/user-attachments/assets/a79f708a-8a5f-4df3-8933-e9a41dd56108" />

5. What is the standard port used for the HTTPS protocol?
- 443

6. What is a folder called in web-application terminology?
- Directory

7. What is the HTTP response code is given for 'Not Found' errors?
- 404

8. Gobuster is one tool used to brute force directories on a webserver. What switch do we use with Gobuster to specify we're looking to discover directories, and not subdomains?
- dir

9. What single character can be used to comment out the rest of a line in MySQL?
- #

10. If user input is not handled carefully, it could be interpreted as a comment. Use a comment to login as admin without knowing the password. What is the first word on the webpage returned? 
- congratulations
to see what to get after we solved the machine i do try some payloads on login page of the IP and then i get this message and flag after i inter this payload: " OR 1=1 --   for username and password for both then it successfully execute and give me the message 
  
11. Submit root flag
- successfully solved

