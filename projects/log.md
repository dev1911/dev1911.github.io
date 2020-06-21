---
layout: project
type: project
image: images/log/linux.jpg
title: Centralised Log Server
permalink: projects/centralised-log-server
# All dates must be YYYY-MM-DD format!
date: 2019-10-01
labels:
  - Linux
  - Socket Programming
  - Python
  - Log management
summary: A centralised log system for Linux based operating systems.
---

Project done as part of "Data Communication and Computer Networks" course.  

## Features
* Sets up cron jobs to send logs of different types to a central server. 
* User can set the frequency of the cron job and also set priority levels for various log files.  
* Centralised server receives logs and stores in a file system into different directories based on the client's IP address and the type of log received (syslog , ssh logs , etc). 

## Tech Stack
* Python :- For socket programming and setting up of cron jobs.

Source: <a href="https://github.com/NikhilMJagtap/Centralised-Log-System"><i class="large github icon"></i>Centralised Log System</a>