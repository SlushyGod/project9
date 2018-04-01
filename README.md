# Project 9 - Honeypot

Time spent: **8** hours spent in total

> Objective: Setting up a honeypot to demonstrate its effectiveness at detecting and/or collecting data about an attack.

## Honeypots used:
Dionaea
Cowrie
Snort

##Issues encountered:
--Could not create projects with a Mississippi State email address so I had to use my own.
--I also had to set a firewall rule to accept port 80 traffic so I could connect to the mhn dashboard.
--Trying to export the session.json file did not go well. I was receiving errors that the mhn-admin did not have remote sources for PuTTY. I ssh into the vm and tried installing PuTTy, but that did not help either. I tried to search this online, but did not find sufficient material to help me. There are two GIFs here; one that shows the error I was coming across, and the other one shows what "attacks" I saw in my honeypots. I ended up spending more time on this than the actual project.
<img src="https://github.com/SlushyGod/project9/blob/master/command_prompt.gif">

##Summary:
I started the three honeypots on 3/24, other than the nmaps scans that I did, there was only one new attack which was on the same day and was from Russia. It was actually cool to see this, and the attack wasn't using a "normal" port (http, tcp, etc). It was using port 30452 and the protocol was pcap. However, I was concerned that out of the whole week I let the honeypots hide, they only received one attack. I probably should have checked them during the middle of the week to try and figure out why this was happening so that I could capture moar data.
<img src="https://github.com/SlushyGod/project9/blob/master/honeypot.gif">

##Questions:
No questions.

## Assets
Gcloud platform
mhn-admin
nmap
