# Project 8 - Pentesting Live Targets

Time spent: 4 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: Session Hijacking - https://media.giphy.com/media/cC9Ue0QQo1ib4jwFW2/giphy.gif

Vulnerability #2: SQLi - https://media.giphy.com/media/1yiv7ybde4vkwQiZzZ/giphy.gif

## Green

Vulnerability #1: User Enumeration - https://media.giphy.com/media/1ymLwhD3fxVica9C6b/giphy.gif

Vulnerability #2: XSS - https://media.giphy.com/media/iBiU5NBSZ2qbbkxBmy/giphy.gif


## Red

Vulnerability #1: CSRF - https://media.giphy.com/media/3FQ87ny3D3sgVFRboF/giphy.gif - The server does not authenticate the CSRF token when editing user information, meaning data such as passwords can be changed without a valid CSRF token.

Vulnerability #2: IDOR - https://media.giphy.com/media/1UKYPw5lMi8WzrX69q/giphy.gif



## Notes

Describe any challenges encountered while doing the work

