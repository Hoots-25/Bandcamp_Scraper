### Bandcamp Web Scraper

## Purpose
The objective of this project was to develop, test, and verify a web scraper to crawl across Bandcamp artists' pages.
The data collected includes artist genres, song/album names, track lengths, and release dates, and number of listens.
Users can manipulate this data to undercover trends over time, or make comparisons to other artists or genres.

## How
The web scraper utilizes Beautiful Soup, NumPy, Urllib, & CSV libraries.
The Urllib library was used to send requests for Beautiful Soup to parse and make readable for the scraping.
With Beautiful Soup, I was able to create functions to read artist URLs, their albums/tracks, track lengths, and release date.
All of this data was compiled and written to a CSV file for cleaning later on.


## Lessons Learned 
Websites can be complicated! This was the first webscraper I've created, and it taught me a tremendous amount about the subtle intricacies of HTML and how to best utilize Beautiful Soup. There were numerous cases I ran into that scraping functions I created could not be used. I noticed this when some artist pages looked different, or contained multiple tabs of albums. I concluded that further functions or 'if' statements to look for the intracacies and further develop the scraper to not throw errors or scrape more data.
