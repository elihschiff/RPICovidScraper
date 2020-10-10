RPI Covid Dashboard Scraper
----------------------------

Scrapes https://covid19.rpi.edu/dashboard and (optionally) posts to discord channels using webhooks. It also submits a request to the Wayback Machine / Internet Archive to perform a capture of the site when the data is updated.

# Usage

python3 main.py or ./main.py

See the webhook_urls.py.sample for information on configuring discord webhooks.

# Dependencies
- Python 3.6 or later
- See requirements.txt for python dependencies

# Announcements
Want the webhook in your discord server? Email rpi@johnnyapol.me and I'll add you to my instance.
