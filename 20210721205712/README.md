# How to manage date command to create a ISO version of the curent time and date in UTC
After a 10 minutes hard time trying to figure out how the date command word, I finally can create an ISO version of the current date and time in YYYYMMDDHHmmss format, so I can organize my zet ddirectory
It's actually very simple:
`date -u +%Y%m%d%H%M%S` 
