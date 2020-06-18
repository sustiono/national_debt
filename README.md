# National GDP Scrapy

Scrap national GDP from https://worldpopulationreview.com/countries/countries-by-national-debt/ using Scrapy

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install some packages needed.

```bash
pip install -r requirements.txt
```

## Usage
Choose one of the commands below to get the results in the desired format

```bash
scrapy crawl countries -o world_population.csv
scrapy crawl countries -o world_population.json
scrapy crawl countries -o world_population.xml
```