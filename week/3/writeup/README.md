Writeup 3 - OSINT II, OpSec and RE
======

Name: Jonathan Cheek
Section: 0101

I pledge on my honor that I have not given or received any unauthorized assistance on this assignment or examination.

Digital acknowledgement of honor pledge: *PUT YOUR NAME HERE*

## Assignment 3 Writeup

### Part 1 (100 pts)
*INPUT YOUR RESPONSE TO THE PROMPT HERE*
  Many of the vulnerabilites have simple fixes that would make it much more difficult to break into the server. Some of the of vulnerabilites include weak passwords, exposing critical personal information, and exposing critical product information. Regarding the weak passwords, they are two problems. First, ports that are being used by the application should be closed. If these ports need to be open, they are more secure methods of authenticating user identification than a traditional username and password login prompt. If you still choose to use a username-password login system, the password should be much more complicated. Many automated scripts use a list of common passwords to attempt to break into a system. By using more complex the chances of unauthorized users gaining access to a system decreases dramatically. A good password should have a mix of numbers, letters, and special characters.

  Another issue was how easy it was to gain personal information that aided in compromising the server. The more personal information attacker has about you, the better the potential social engineering scam can be. Based on how informal the username kruegster1990 is I'm assuming the social media are meant to be more personal.  In this case, make social media accounts private so attackers cannot get information from your accounts. If the accounts are meant to represent the company, having a link to the company website would not a problem if it did not lead to what may be the biggest vulnerability.
  
  A major problem was the server's IP address was visible in the page's source code as well as the url search bar. This is a public facing webpage which was linked to by a public social media page so it was not hard to find. Once an attacker gets an IP address, they have accomplished one part of the battle and can then establish an plan to break into the server with that IP addresss. To fix this, change the link in the html code to something like "admin.html" so the IP address is not exposed when users navigate to that page. 
