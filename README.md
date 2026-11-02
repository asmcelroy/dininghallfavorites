# Purdue Dining Alert

# Project goal:
My goal is to create a script that runs each day and will notify me if my favorite foods are being served at any select Purdue dining halls.

# MVP scope:
- read list of fav foods from favorites.txt
- fetch menu with curl
- parse item names with jq
- match items with grep -i
- label match with dining court
- send matches to phone
- run every morning with cron

# Future plans:
- dietary filters
- meal-period filter
- no repeat alerts

# Tech stack:
- bash

- curl
- jq
- grep -i -f
- date
- cron

- purdue dining menu API
- ntfy.sh
