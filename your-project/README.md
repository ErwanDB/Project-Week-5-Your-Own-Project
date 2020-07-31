<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Guitar Chords
*Erwan de Boisjolly*

*Data Analytics - Barcelona - June 2020*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
I started learning guitar on my own nearly two years ago. I was already playing some melodies on ukulele and I wanted to try to play those ukulele songs on guitar. I found some were very easy and others more complicated to play. Youtube is full of videos were people shows how to play various songs with only few chords. From this the below questions came in mind.

## Questions & Hypotheses
- How many songs can be played with a beginner level ?
- What chords do you need to learn ?
- What is the proportion of songs that can be played with those chords ?

## Dataset
To conduct this project, I used a web site called [Ultimate-Guitar](https://www.ultimate-guitar.com) where you can find more than 600 000 guitar tabs. There are actually tabs for ukulele as well and other instruments. I personally use this website when I'm looking for a tab.
I scraped from this website the "1 000 most popular songs of all times" with their artists, chords, rating and votes. Popularity is measured here by the number of "hits" (click) on the tab's page. 1 000 songs was the maximum display on the web page that could be scraped.

## Workflow
After scraping the data from the web site, I looked at the frequencies of the chords in the songs. I then classified them in three levels of difficulty and assign a beginner, intermediate or advanced level to the songs.

## Organization
The project was planned and led using a [Trello](https://trello.com/b/BM3ag3la) bord.

The repository is composed of the following files:

- Datasets folder with 4 files:
	1. Chords_encoded.csv: data scraped from the website with the chords encoded
	2. Chords_clean.csv: cleaned data used for the analysis
	3. chords.xlsx: chords export to ease data visualisation with Tableau
	4. level.xlsx: figures summary by level
- Notebooks folder with 4 notebooks:
	1. data_scraping.ipynb: code for scraping
	2. data_cleaning.ipynb: code for data cleaning and transformation
	3. data_analysis.ipynb: exploration, analysis and insights
	4. technical_paper.ipynb: other insights and potential way forward for the project
- Presentation folder: contains a PDF presentation with the main insights.
- The current README file

## Links

[Repository](https://github.com/ErwanDB/Project-Week-5-Your-Own-Project.git)  
[Trello](https://trello.com/b/BM3ag3la)
[Tableau](https://public.tableau.com/views/Chords/Dashboard1?:language=fr&:display_count=y&publish=yes&:origin=viz_share_link)