# data-scrape

## Objective
Web scraping is extracting data from websites. In this project, you'll be scraping data from Yahoo's Finance section.
More specifically, you'll be harvesting the company name and stock price of a very famous social media company. You've been giving them a lot of your data, now it's time to return the favor.

## Getting Started

### Install packages

If you haven't already, you will need to install the following packages:

* pip - `easy_install pip`
* Beautiful Soup - `pip install BeautifulSoup4`


### Import Libraries

1.  Create a file called `app.py`
2.  Create a file called `index.csv
3.  At the very top of `app.py` import your libraries:

```
import urllib2
from bs4 import BeautifulSoup
```

### Save and load population data from `data.json`

1.  In `data.json` copy and paste the data from: https://gist.github.com/mellaniesoriano/901fe8f86eb8441f50a42963930d1b28
2.  In `main.py`, create a variable called `filename` and set it's value to `"data.json"`
3.  Open the file using the following method:

```
with open(filename) as dataset:
  pop_data = json.load(dataset)
```

