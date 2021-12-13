# CS:GO Tournament Statistics & Predictor

Gathering statistics about the game Counter-Strike: Global Offensive, specifically tournament matches played by professional teams from HLTV.org by web-scraping. 
Data is transpiled into visualized graphics and graphs, and we work with algorithms to predict future tournaments compiled of teams.

## Technology
Python 3.7.X
- PyPlot
- Numpy
- Pandas
- BS4
- Selenium
- Jupyter Notebook
  - ipywidgets

## Getting started
### Installation
Use the install instructions from the [dat4 python setup guide](https://github.com/Hartmannsolution/docker_notebooks/blob/master/notebooks/01-0%20Getting%20Started%20with%20installations%20etc.ipynb).

### Usage
Run the notebooks in order.


## Status & Reflections
We were very ambitious in the beginning of the project. We wanted to explore machine learning algorithms in depth while working with ton of statistics. Unfortunately, the data required is not something that was as easily accessible as we initially thought.

Our project shifted focus from feeding data to finding data. This kind of data isn’t accessible with any free public API, so web-scraping was put into the works. We were unable to web-scrape tons (tens of thousands) of matches pages as the processing power and time would be too vast, so for our project we decided to have more basic statistics instead, but a lot of it. 

---

We still work with predictions as initially intended and we work with graphs and statistics to give an estimated guess on future tournaments which is what we ought to do in the first place.
