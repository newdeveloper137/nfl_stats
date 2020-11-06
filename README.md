# Nfl_stats Project

This project is attemtping to scrape web stats from the NFL, replicate the sites where the NFL stats were found in the form of html tables, and then have a quiz where users can take a quiz about all of the stats on the site. This uses the Django framework in order to render the content to the web.

However, I am running into many problems.

Checklist for next week:

- [] Figure out a way to make the code work all of the time (quiz is working about half of the time, but then breaks)
- [] Determine why the quiz is breaking
- [] Investigate React.js as a potential solution
- [] Figure out a way to use models.py in conjunction with the /Admin built-in feature of Django and then use the stats inside of there as a REST API so that the quiz will work 100% of the time. I can get the stats into the /admin as a class Rb, but the stats are static once they arrive, they do not change when the stats change on the home site where the stats were initially scraped from.
- [] Finish writing the JavaScript for the Passing stats as well as the Defense
