---
date_creation: <% tp.file.creation_date("YYYY-MM-DD") %>
time_creation: <% tp.file.creation_date("HH:mm:SS") %>
last-modified: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
tags:
  - weeklynotes
---
- prev wr:: <% `[[w-${moment().format("YYYY")}-W${moment().subtract(1, 'weeks').format("ww")}]]` %>
- [[gtd - projects]] look here for some things to do for the week
	- take those things and put them here, for you to see.
- each day, look at stuff from this file to find what to work on.

- what am I doing this week?
	- [ ] <% tp.file.cursor() %>