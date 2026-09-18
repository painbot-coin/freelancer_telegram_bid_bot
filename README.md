# Freelancer bid bot

Python bot that searches Freelancer.com for scraping jobs, scores them, places a bid from a budget formula, and sends the project link to Telegram.

## What is in here

- Freelancer SDK session and project search
- Bid placement with amount/period/milestone rules
- Telegram `sendMessage` alerts

Configure `FLN_URL`, Freelancer OAuth, and Telegram tokens via environment variables. Do not commit tokens.

## Stack

Python, Freelancer SDK, Telegram Bot API
