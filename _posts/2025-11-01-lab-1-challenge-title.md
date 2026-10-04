---
title: "Lab 1: Getting Started"
date: 2025-11-01 10:00:00 +0300
categories: [Lab Challenges, Network]
tags: [nmap, enumeration, Hack The Box]
toc: true
---

**Platform:** Hack The Box  
**Category:** [Network]  
**Difficulty:** Hard

## Problem statement

This section covers terms such as shell, port, and web server. All these three play a role in the infosec space and also vulnerabilities that are common with web applications have been stated. It has covered the OWASP top ten vulnerabilities
## Approach

1. I spawned a target using the HTB Parrot OS and opened the machine. I then wrote the command netcat 152.57.164.82 30700 which gave the banner.

## Tools used

netcat

## Screenshots

<!-- Upload your screenshots to assets/img/labs/ then remove the arrows around the lines below
![What this shows](/assets/img/labs/lab1-a.png){: w="700" }
_[Caption: what this screenshot shows.]_

![What this shows](/assets/img/labs/lab1-b.png){: w="700" }
_[Caption: what this screenshot shows.]_
-->

[Screenshots go here.]

## Key lessons learned

Netcat can be used to determine which services are running on a particular port. As of this case it is SSH.
