---
date_creation: <% tp.file.creation_date("YYYY-MM-DD") %>
time_creation: <% tp.file.creation_date("HH:mm:SS") %>
tags:
  - weeklynotes
---
- prev wr:: <% `[[w-${moment().format("YYYY")}-W${moment().subtract(1, 'weeks').format("ww")}]]` %>
- make a new week note: [[week review checklist]]
- projects:: [[gtd - projects]]
	- take things from projects and put them here. execute
	- each day, look at stuff from this file to find what to work on.

## - what is the project for this week?
- What's the single focus?

## - who do I want to hang out with?
- [ ] call Grandma

## - slowdrip
- [[slow_drip - how to]] (delete me after four are picked)
1. 
2. 
3. 
4. 

##  - what am I doing this week?
- [ ] <% tp.file.cursor() %>

## - reflection
- 