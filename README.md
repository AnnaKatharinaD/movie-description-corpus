# Corpus for Movie descriptions, PG ratings, and information for parents
A small corpus containing descriptions, plot outlines, PG-ratings, genres and parental advisory information of movies from 1996-2021.
Data scraped from IMDB.

## Data:
- *id:* IMDB id 
- *length:* movie length in minutes
- *year:* release year of movie
- *rating:* MPAA rating (G, PG, PG-13, R, or NC-17)
- *reason:* reasoning for age appropiateness rating
- *genre:* list of genres for movie
- *description:* One sentence short description of the plot
- *plot:* One to two paragraph plot outline, includes more details than the description
- *nudity:* How much nudity or sexuality is shown or implied? Based on community vote (none, mild, moderate, severe)
- *violence:* How much violence or gore is shown?
- *profanity:* How much profanity or strong language is featured?
- *alcohol:* To what degree are alcohol and other drugs used or being implied to be used?
- *frightening:* To what degreee are frightening or intense scenes featured, or could the general tone be distressing to younger viewers?

## Example:

| id | length | title | year | rating | reason | genre | description | plot | nudity | violence | profanity | alcohol | frightening |
|----|--------|-------|------|--------|--------|-------|-------------|------|--------|----------|-----------|---------|-------------|
|  tt0319343  |    97    |  Elf     |  2003    |    PG    |    Rated PG for some mild rude humor and language    |   ['Adventure', 'Comedy', 'Family', 'Fantasy', 'Romance']    |    Raised as an over-sized elf, a human travels from the North Pole to NYC to meet his biological father who doesn't know he exists and is in desperate need of some Christmas spirit.        |   Buddy was a baby in an orphanage who stowed away in Santa's sack and ended up at the North Pole. Later, as an adult human who happened to be raised by elves, Santa allows him to go to New York City to find his birth father, Walter Hobbs. Hobbs, on Santa's naughty list for being a heartless jerk, had no idea that Buddy was even born. Buddy, meanwhile, experiences the delights of New York City (and human culture) as only an elf can. When Walter's relationship with Buddy interferes with his job, he is forced to reevaluate his priorities.   |    mild    |     mild  |     mild     |     mild    |     none        |
|    |        |       |      |        |        |       |             |      |        |          |           |         |             |
|    |        |       |      |        |        |       |             |      |        |          |           |         |             |
