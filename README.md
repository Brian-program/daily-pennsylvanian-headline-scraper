# Basic Web Scraper for the Daily Pennsylvanian's Podcast
This scraper updates the daily_pennsylvanian_podcasts.json file daily, but updates the github actions every 6 hours.

This scrapes the podcast page for the most recent Podcast episode.

One major change from the original scraper was the get request link and the targeted element due to the unique id of the "a" class. I had to find a more general header that contained the title instead of the class "a" tag, and using BeautifulSoup, I managed to pull the top title for daily updates.
