# Project 9 - Honeypot

Time spent: **8** hours spent in total

> Objective: Setup a honeypot and intercept some attempted attacks in the wild


**Deployed Honeypot** -

I deployed Dionaea over HTTP, a honeypot used to trap malware samples.


**Issues** -

I had to manually allow HTTP traffic within the mhn-admin settings in order to access the mhn-admin external IP in a browser.

I also ran into issues trying to download the data - I found the resolution at: https://discussions.codepath.com/courses/cybersecurity_university/questions/retrieving-session-json


**Summary** -

There are currently 1154 attacks and this number is continuously increasing.

While the majority of the attacks originated in the United States, there were also numerous attack originating from other countries.

The TOP 5 Attacker IPs:
  76.104.97.242 (1,041 attacks)
  119.191.58.91 (20 attacks)
  191.101.167.7 (12 attacks)
  77.72.82.147 (4 attacks)
  95.215.1.37 (4 attacks)
  
The TOP 5 Attacked ports:
  23 (31 times)
  3306 (21 times)
  80 (8 times)
  445 (7 times)
  5950 (4 times)

The full data is contained within the repository [here](https://github.com/mariahamaris/Codepath-Assignment-9/blob/master/session.json)
