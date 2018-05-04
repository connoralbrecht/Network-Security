Project 8 - Pentesting Live Targets

Time spent: 8 hours spent in total

    Get hands-on experience with some of the most common security exploits through an applied hacking exercise.

Pentesting Report

Blue:
  1. SQLi salesperson id URL
    -GIF Walkthrough: https://github.com/connoralbrecht/CodePath-Week-8/blob/master/Blue%201%20-%20SQLi.gif
  2. Session Hijacking copying and using ppersons session id to get their login access privledges
    -GIF Walkthrough: https://github.com/connoralbrecht/CodePath-Week-8/blob/master/Blue%202%20-%20Session%20Hijacking.gif
Red:
  1. Username Enumeration: "Log in unsuccessful" only bolded for real users with wrong password
    -GIF Walkthrough: https://github.com/connoralbrecht/CodePath-Week-8/blob/master/Red%201%20-%20IDOR.gif
  2. Cross-Site Scripting: Alert message submitted in Feedback on Contact us page
    -GIF Walkthrough: https://github.com/connoralbrecht/CodePath-Week-8/blob/master/Red%202%20-%20CSRF.gif
Green:
  1. IDOR: Change Salesperson ID in URL to '11' which is not linked to on the salesperson page (fired)
    -GIF Walkthrough: https://github.com/connoralbrecht/CodePath-Week-8/blob/master/Green%201%20-%20User%20Enum.gif
  2. CSRF: submit link to edit_salesperson.html script in Feedback that changes salesperson info with id=5 when clicked on by admin. 
    -GIF Walkthrough: https://github.com/connoralbrecht/CodePath-Week-8/blob/master/Green%202%20-%20XSS.gif
    
Assets

edit_salesperson.html link: https://github.com/connoralbrecht/CodePath-Week-8/blob/master/edit_salesperson.html


GIFs created with LiceCap.
