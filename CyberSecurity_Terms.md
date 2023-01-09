<h2>Terms & Defenitions:</h2>

1. Security Assets - Security Assets are critical resources which maintain the working of your company and have to be protected for the continuity of your business.
    1. People - Everyone from the security guard to the top most CEO and founders on the board.
    2. Process - The procedures for doing the successful completion of work from start to finish.
    3. Technology - All the software and hardware related tools and machinery which are critical for the company’s day to day activities.
2. CIA triad - It is model designed to guide policy formation for information security within an organization.
    1. Confidentiality - The quality that only the appropriate person can see the appropriate data and no one else.
    2. Integrity - The quality that the data does not get changed without the consent of the original owner.
    3. Availability - The quality that the processes are up and ready to use even in unfavorable conditions.
3. Cybersecurity Frameworks - They are the guidelines, standards, and best practices for risk management in a company.
    1. NIST cybersecurity framework - They are released by the US national Institute of Standards and Technology for risk management. They consist of five stages: identify, protect, detect, respond and recover. The first two stages happen before an incident and the next three after it.
4. Vulnerability - A vulnerability refers to any weakness that is present in your security assets.
5. Exploit - An exploit is way or a procedure to make use of the vulnerability to get a desired result which may or may not be malicious.
6. Risk - Risk is a probability that a vulnerability can be exploited. It can be expressed either qualitatively (risk matrix, risk pie chart, ...) or quantitively (percentage, scale, ...).
7. Incident - An incident refers to an event where the vulnerability has been exploited and there is a loss for the business.
8. Threats - Threats are factors that can affect the working of a company.
    1. Natural disasters - Earthquakes, Tsunamis, Tornado, …
    2. Environment Threats - Temperature, Humidity, pollution, …
    3. Human threats - These are the most common threats a cyber security professional deals with.
        1. APTs : Advanced Persistent Threats are nation state actors and groups that have the latest technology and immense financial resources.
        2. Cyber Criminals : They are the malicious actors whose main goals are to steal money or get a financial incentive.
        3. Hacktivists : They are groups of people who have a common ideology and want to promote it by attacking other groups of different ideology. Example - anti-abortion, religious, ..
        4. Script Kiddies : These are people without technological knowledge but can do simple point and click hacking and follow tutorials to bypass security limitations.
        5. Insider threats : These can either be malicious or non malicious actors who cause damage to the company by either not being aware or intentionally leaking secrets.
9. Reverse Shell - The attacker opens up a listening port and the victim connects to the attacker's machine with a shell terminal. This is the most commonly used form.
10. Bind Shell -  The victim opens up a listening port with shell executing on it and the attacker connects to the victim's machine.
11. Staged Payload - The payload is splitted up and send to the victim machine. It is less stable. In metasploit, the stage payloads are seperated by '/'.
12. Non-Staged Payload - The payload is send all at once to the victim machine. High chances of not working and getting detected by Anti-virus. In metasploit, the non-staged payloads are seperated by '_".
13. Gaining Root - The process of exploiting a vulnerability in a victim's machine and gaining access to the root user.
14. Manual Exploitation - Either creating a payload manually for a vulnerability or finding a payload online for the exploitation and not using automatic tools like metasploit.
15. Brute Force attacks - Trying out every combination of username and passwords one after the another to get access.
16. Credential Stuffing - Injecting breached credentials in hope of getting access.
17. Passweord Spraying - Using known usernames without knowing the passwords. 
18. SQL injection - SQL injection is a web security vulnerability that allows an attacker to interfere with the queries that an application makes to its database. It generally allows an attacker to view data that they are not normally able to retrieve. A site that is apparently vulnerable to SQLi can be detected just from weird behaviour of the server when dealing with SQLi related inputs. The only sure way to prevent SQL Injection attacks is input validation and parametrized queries including prepared statements.
19. XSS - Cross site scripting is when the application/browser runs arbitrary scripting commands from the user and has no defence in place against them. Mitigations for XSS typically involve sanitizing data input (to make sure input does not contain any code), escaping all output (to make sure data is not presented as code), and re-structuring applications so code is loaded from well-defined endpoints.
20. XSRF or CSRF - Cross-site request forgery, also known as one-click attack or session riding and abbreviated as CSRF or XSRF, is a type of malicious exploit of a website or web application where unauthorized commands are submitted from a user that the web application trusts. The major difference between this and XSS is that a malicious action takes place in XSRF always. The most effective method of protecting against CSRF is by using anti-CSRF tokens.
21. Heartbleed attack - It was a common security bug in SSL. Where the attacker was able to read the memory of the server and decrypt the private key. Thereby the attacker was able to impersonate the server.
22. Poodle attack - It is a security vulnerability that takes advantage of the fallback to SSL 3.0. Thereby allowing the attacker to decrypt the messages in the middle.
23. Snort signature - Also called a snort rule is basically conditions set in SNORT (NIDS) to characterise malicious activity in the network.
24. IDS - Intrustion detection system is similar to a web camera that takes note of malicious activity in your network or host.
25. IPS - Intrusion prevention system is similar to a secuirty gaurd that not only notices the malicious activity but can also be advised to do certain actions in various scenarios.
26. Incident response - Incident response or IR is a structured process organizations use to identify and deal with cybersecurity incidents as described by NIST. It includes the stages of Preparation; Detection and Analysis; Containment, Eradication, and Recovery; and Post-Event Activity.
27. Security information and event management (SIEM) - A security solution that helps organizations detect threats before they disrupt business. Examples: Fortinet, IBM QRadar, McAfee SIEM, and Splunk.
28. Managed Detection and Response (MDR) - MDR Security service providers will investigate an alert and determine whether it is a true incident or a false positive. This is accomplished through a combination of data analytics, machine learning, and human investigation.

