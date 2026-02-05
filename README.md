<!-- Banner ASCII -->
 ```
                   _        _        _______  _______  _______  ______  _________ _       __________________         
|\     /||\     /|( \      ( (    /|(  ____ \(  ____ )(  ___  )(  ___ \ \__   __/( \      \__   __/\__   __/|\     /|
| )   ( || )   ( || (      |  \  ( || (    \/| (    )|| (   ) || (   ) )   ) (   | (         ) (      ) (   ( \   / )
| |   | || |   | || |      |   \ | || (__    | (____)|| (___) || (__/ /    | |   | |         | |      | |    \ (_) / 
( (   ) )| |   | || |      | (\ \) ||  __)   |     __)|  ___  ||  __ (     | |   | |         | |      | |     \   /  
 \ \_/ / | |   | || |      | | \   || (      | (\ (   | (   ) || (  \ \    | |   | |         | |      | |      ) (   
  \   /  | (___) || (____/\| )  \  || (____/\| ) \ \__| )   ( || )___) )___) (___| (____/\___) (___   | |      | |   
   \_/   (_______)(_______/|/    )_)(_______/|/   \__/|/     \||/ \___/ \_______/(_______/\_______/   )_(      \_/   
                                                                                                                     
                                                                                  
                                                                                                                                      
```
---
# 💊 Learning Of

1. **What it's Vuln Or Vulnerability** : which refers to a vulnerability, weakness, or security gap in a computer system, network, or application. In the IT world, a vulnerabilities refers to system weaknesses that attackers can exploit to infiltrate, steal data, or damage the system.

2. **How can I know That's Website It's Vulnerability** : Website vulnerabilities are weaknesses in a site's code, configuration, or infrastructure that could allow attackers to exploit them, such as injecting malicious code, stealing data, or gaining unauthorized access. Common types include SQL injection, XSS (Cross-Site Scripting), CSRF (Cross-Site Request Forgery), and misconfigurations. Knowing these helps in securing your own site or assessing risks ethically.

Important Note: Always ensure you have explicit permission to test any website. Unauthorized scanning or testing can be illegal (e.g., violating laws like the Computer Fraud and Abuse Act in the US). Focus on your own sites or use legal platforms like bug bounty programs (e.g., HackerOne, Bugcrowd) where testing is encouraged.

## 🌡️ SQL injection | XSS | CSRF 

⁂ **SQL Injection (SQLi)** is a code injection technique that exploits vulnerabilities in web applications that interact with databases. It occurs when an attacker inserts malicious SQL code into a query, potentially allowing them to read, modify, or delete data, bypass authentication, or execute administrative operations. It's one of the oldest and most dangerous web vulnerabilities, often due to poor input handling.

SQLi is possible because many apps build SQL queries by concatenating user input directly into strings, without proper validation or parameterization.

⁂ **Cross-Site Scripting (XSS)** : Cross-Site Scripting (XSS) is a type of injection attack where malicious scripts are injected into otherwise benign and trusted websites. It allows attackers to execute scripts in a victim's browser, potentially stealing sensitive information like cookies, session tokens, or personal data, or redirecting users to harmful sites. XSS is a client-side vulnerability, ranking high in the OWASP Top 10, and often stems from improper handling of user-generated content.

Unlike server-side attacks (e.g., SQL injection), XSS affects the end-user's browser, exploiting the trust between the user and the website.

⁂ **Cross-Site Request Forgery (CSRF)** : Cross-Site Request Forgery (CSRF) is an attack that forces an end user to execute unwanted actions on a web application in which they are currently authenticated. Unlike XSS (which injects scripts) or SQL injection (which manipulates databases), CSRF exploits the trust a site has in the user's browser, tricking it into sending forged requests. It's in the OWASP Top 10 and can lead to actions like changing passwords, transferring funds, or deleting data without the user's consent.

CSRF works because browsers automatically include credentials (e.g., cookies) in requests to trusted sites, even if initiated from an external malicious page.


*All article sources come from: BlackBox AI*

