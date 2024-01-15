# Welcome to My Vivino
***

## Task
The task here was to develop and analyze a wine database, and 
then to provide users with a search tool that allowed 
specifications of meal-pairing, general wine attributes, and 
tasting notes.

## Description
The project consisted of a series of stages culminating in 
a search tool that users interact with in order to find the 
best wine in light of their preferences. The structure of the 
notebook is as follows:
#### 1. Get URLs for each wine 
#### 2. Get HTML for each wine 
#### 3. Loading the data (start executing here after imports)
#### 4. Data exploration and visualization
#### 5. Rank wines based on rating and price 
#### 6. General wine search
#### 7. Search for wines based on notes
#### 8. Wine-food pairing
#### 9. Comprehensive search
Selenium, bs4, asyncio, and aiohttp were used in accessing 
wine html. Core data anlaysis and modeling tools included 
pandas, numbly, matplotlib, sklearn, and seabord. Language 
models for the notes-based search involved nltk and sklearn. 
Food-wine pairing was based on selections by Nikita who also 
has a wine certification. Finally, the comprehensive search 
combines three search filters and sorts by a calculated quality 
factor based on both price and rating.


## Installation
The program requires Jupyter Notebook functionality with the 
following packages: asyncio, aiohttp, lumpy, pandas, matplotlib, 
Sklearn, seaboard, nltk, selenium, and bs4.

## Usage
The wine database was already saved to an SQL db. Do not run 
the notebook from the beginning unless you wish to recompile 
the database. After executing the imports cell, the notebook 
can be executed starting in section 3, “Loading the data.”
All cells after this point can be executed sequentially, with 
user prompts being requested following the execution of search
methods. The user can enter text directly or elect to enter 
nothing, which broadens the results. Output from the search
tools and their results may require opening the text in another
window (VS code), or it may be viewed directly below the 
execution cell (Anaconda). Searches can be re-executed by 
simply running the search cells again. 

### The Core Team
Andrew Bonham and Nikita Gaidamachenko

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>

