# Project 9 - Honeypot

Time spent: **8** hours spent in total

> Objective: Setup a honeypot and intercept some attempted attacks in the wild

**Deployed Honeypot** -

I deployed Dionaea over HTTP, a honeypot used to trap malware samples.

**Issues** -

I had to manually allow HTTP traffic within the mhn-admin settings in order to access the mhn-admin external IP in a browser.

I also ran into issues trying to download the data - I found the resolution at: https://discussions.codepath.com/courses/cybersecurity_university/questions/retrieving-session-json

**Summary** -

Number of attacks: 1154 and counting.

While the majority of the attacks originated in the United States, there were also numerous attack originating from other countries.

The data is contained within this repository [here](https://github.com/mariahamaris/Codepath-Assignment-9/blob/master/session.json)
