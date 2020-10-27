# National GDP Scrapy

Scrap national GDP from https://worldpopulationreview.com/countries/countries-by-national-debt/ using Scrapy

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install some packages needed.

```bash
git clone git@github.com:sustiono/national-debt-scrapy.git
cd world-population-scrapy
pip3 install virtualenv
virtualenv .env
source .env/bin/activate
cd national_debt
pip install -r requirements.txt
```

## Usage
Choose one of the commands below to get the results in the desired format

```bash
scrapy crawl gdp_debt -o world_population.csv
scrapy crawl gdp_debt -o world_population.json
scrapy crawl gdp_debt -o world_population.xml
```
