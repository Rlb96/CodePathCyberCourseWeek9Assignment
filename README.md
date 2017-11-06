# CodePathCyberCourseWeek9Assignment

Time spent: 6 hours spent in total

> Objective: stand up basic honeypots and demonstrate their effectiveness at 
			 detecting and/or collecting data about an attack.

### Honeypots Deployed

- [x] dionea
- [x] amun
- [x] snort
- [x] glastopf


### Issues encountered

- [x] One issue I hit is that some honeypot types just didn't seem to attract 
	  any attacks. Oddly enough sometimes running the suggested nmap command against
	  the server as a test didn't even get registered by the MHN software. I usually killed these 
	  VMs and created new ones. Not sure if the problem was set up or a bug in MHN. 


### Data summary
 
- [x] dionea Honeypot caught 12501 attacks
- [x] amun Honeypot caught 1,089 attacks 
- [x] snort Honeypot caught 694
- [x] glastopf Honeypot caught only 7 attacks. 
- [x] Unfortunately, no malware samples were caught. 


### Questions

- [x] I noticed a trend of getting consecutive attacks from a particular IP address,
		What I'd like to know more about is what is the reason for this series of attacks? 
		Is it an attempt at a simple DDOS? Is the same attacker trying multiple attacks? 
		Could the attacker be employing some form of machine learning to improve the attack?
