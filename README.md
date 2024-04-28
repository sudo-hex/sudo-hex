```console
user@gitreadme:~$ cat ./readme.txt
zsh: permisssion denied: ./readme.txt

user@gitreadme:~$ cat /etc/passwd | awk -F: '{print "User:", $1, "UserID:", $3, "GroupID:", $4, "Home:", $6, "Shell:", $7}'
User: root UserID: 0 GroupID: 0 Home: /root Shell: /usr/bin/zsh
User: user UserID: 1000 GroupID: 1000 Home: /home Shell: /usr/bin/zsh

user@gitreadme:~$ ./sudohex -vvv
SudoHex v0.1 - Exploiting suid vulnerability
[+] Escalating privileges to root...

[>] Grabbing available SUIDs
[>] Found : nmap 2.02 with suid
[>] Run : nmap --interactive 
[>] Input : !sh

[+] Privilege escalation complete.
[root@gitreadme]# cat ./readme.txt
``` 

### Introduction 
Cybersecurity professional,  Red Team wannabe, CTFer and Oh... SINT 

### Expertise
- **Security Frameworks** : Implementing industry-standards methodologies accross multiple verticals.
- **OSINT** : *Why do I need privacy ? I have nothing to hide !* A few moments later --> :suprised_pickachu_face: 
- **Ethical Hacking** : Breaking into systems and reporting flaws.
- **Cybercrime prevention** : Helping lawyers talk to engineers.


<!--
**sudo-hex/sudo-hex** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
