---
layout: default
title: "Blog #5: Threat Hunting with Splunk & Sysmon Event Logs"
date: 2025-07-09 00:05:00 +0000
---

![Splunk Search Example]({{ site.baseurl }}/assets/images/SplunkThreatHunting.png)

Welcome to my blog! My name is Aaron Narayan and this is where I share my cybersecurity projects with Splunk, Linux, VirtualBox, SOC labs, and GRC Documentation & Auditing.  This post contains screenshots from a threat hunting exercise with Splunk and Sysmon Events. I installed the add on to input Sysmon, input a new index of data, and then searched for Indicators of Compromise. Below are the steps covered and a Google Doc containing screenshots. Thank you for visiting. In the next blog I will produce a SOC 2 Report. 

### Covered Modules

 - Install Splunk Add-on for Sysmon
 - Input Sysmonsplunklab Index
 - Find suspicious executable
 - Find hash of suspicious executable
 - Look for Event Code 22 (DNS) At around the Time the File was Executed
 - Find the cloud source associated with the threat via Query name field 
 - Find PDF that was timestomped via EventCode=2 pdf
 - Find where once.cmd was written to via EventCode=11
 - Find destination ip via EventCode=3
 - Find what time was the process terminated via EventCode=5



[**👉(Google Doc: Threat Hunting Walkthrough)**](https://docs.google.com/document/d/1mGThS8IYOFOmBQmkndUu60GrGjCHqDKN0oy0XmU4bUw/edit?usp=sharing)


![CySA+ Course Certification]({{ site.baseurl }}/assets/images/CySA+CourseCertificate.png)

