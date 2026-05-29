# Instagram Bot Using Python

## Overview
An automation bot for Instagram that handles routine tasks such as following/unfollowing, liking posts, commenting, and scraping analytics data.

## Tools & Technologies
- **Python** – Core bot logic
- **Selenium** – Browser automation for UI-based interactions
- **Automation** – Scheduled task runner (APScheduler / cron)
- **Pandas** – Engagement analytics and reporting

## Project Structure
```
instagram_bot_python/
├── bot/
│   ├── login.py
│   ├── follow_unfollow.py
│   ├── like_comment.py
│   └── scraper.py
├── config/
│   └── settings.py
├── analytics/
│   └── report.py
├── requirements.txt
└── README.md
```

## Features
- Auto-login with session persistence
- Targeted follow/unfollow based on hashtag or competitor followers
- Auto-like and comment with randomized delays (human-like behavior)
- Engagement data export to CSV via Pandas
- Rate-limit-aware scheduling to avoid bans

## Setup
```bash
pip install -r requirements.txt
# Set your credentials in config/settings.py
python bot/login.py
```

> ⚠️ Use responsibly and in accordance with Instagram's Terms of Service.
