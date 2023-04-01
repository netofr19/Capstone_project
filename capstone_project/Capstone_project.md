# Capstone Project

## Overview
The year is 2015 and you want to watch a movie in the movie teather. Luckily for you, instead of having to drive all the way to the movie theater and buy your ticket for a show that's happening later that night, there's a website called **Fandango**.

&nbsp;
**Fandango** sell movie tickets online, besides this website algo displays movie ratings.

In that moment, you don't know which movie you're going to watch and you analyze the movie ratings of the website. After watching the movie and not like it, you begin to ask yourself... Is there a conflict of interest for a  website that both sell movie tickets and displays review ratings? Can we answer this with **data analysis**?

Let's see!

 - **Question to answer:** Is there a conflict of interest for a website that both sells movie tickets and displays review ratings? Does a website like Fandango artificially display higher review ratings to sell more movie tickets?

## Details
Fandango has two ratings:
 - STARS
    - Rating in stars 0-5 displayed on their website's HTML.
 - RATING
    - Actual true rating numerically shown on movie's page.

### ```all_sites_scores.csv``` contains every film that has a Rotten Tomatoes rating, a RT User rating, a Metacritic score, a Metacritic User score, and IMDb score, and at least 30 fan reviews on Fandango. The data from Fandango was pulled on Aug. 24, 2015.

### ```fandango_scrape.csv``` contains every film 538 pulled from Fandango.