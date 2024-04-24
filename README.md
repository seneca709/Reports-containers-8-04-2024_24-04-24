# Report 
<b>Period: 8-04-2024 / 24-04-24</b> <br>
In this repository you will find different containers and how I approached the containers.
Due the fact that I am still learning I am still finding a way to report the containers clean. 
The directories are references from the containers. This could contain screenshots of the questions/answers although it also contained evidence. I follow a course which include the theory of cybersecurity and beside learning the theory I try to apply it by practicing with containers which are fictive.

## 1.First machine
This container was part of a excersise from the course Introduction to Cyber security.
At the references directory you can see the flags and the fictive scenario.
### Walkthrough <br>
Aim: Vulnerabilities in banking system. <br>
1.Find potential hidden pages. <br>
In order to find the hidden pages I used gobuster to find the hidden pages. The syntax is as followed: nameoftarget...functiontoitterateofwords<br>
2.Find the infected ip <br>
Clicked through different IP and saw a ip which was red. By clicking the IP I could enter the host of the machine and got a flag which showed that this was the vulnerability. Then I could insert the given information and transfer money . 
## 2.Ricky and morty <br>
Aim: Exploit web server <br>
This Rick and Morty-themed challenge requires you to exploit a web server and find three ingredients to help Rick make his potion and transform himself back into a human from a pickle. <br>
### Walkthrough <br>
1. First ingredient <br>
Through inspecting elements I found the username R1ckRul3s. I tried ip/robots.txt although I only found the text: Wubbalubbadubdub. Than I searched for the login page by using ip/login.php and found on another site the credentials. By going to the commands and enter ls i could find the file Sup3rS3cretPickl3Ingred.txt and saw the first ingredient.
2. Second ingredient <br>
Than I searched through the clue.txt and entered ls /home in the command panel and saw rick. I used this with the command ls -l /home/rick to find the second ingredient. In order to get the second ingredient
3. Third ingredient <br>
I used the command cat /home/rick/second\ingredients. I tried cat and ls although that didnt help. Through searching I found that the right command was with tac. 
## 3.Anthem <br>
This container contained alot of detailed questions and I tried to keep it in a nutshell.
Summary: For this section I learned how to use NMAP to detect different ports. By entering hidden files I could detect which system the target has been using, the password and much more. While navigating through the system I could access the CMS as administrator and find flags. For example there was a flag in the meta tags. See the screenshots at the Anthem directory for details.
