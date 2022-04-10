# Bitcoin Arbitrage Opportunities
The goal of this challenge is to create a Jupyter Notebook that will do the following:

> 1. Pull in historical data trade data from Coinbase and Bitstamp (csv files)
> 2. Use the python library to save data into two distinct dataframes
> 3. Clean and Massage the data i.e prep it for subsequent analysis
> 4. Analyze the data in order to ultimately select time periods where there existed arbitrage opportunities.

## Installation

Activate Conda Dev environment make sure to install the following packages
if you do not have them already:

* pandas
* numpy
* pathlib

While you could use the package manager [pip](https://pip.pypa.io/en/stable/) to install these individually please make use of the requirement text in the repo.

```bash
python -m pip install -r requirements.txt
```

## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Discussion
This is an interesting article about arbitrage of cryptocurrencies that helped to contextualize this coding effort:

**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data Science and Cryptocurrency arbitrage: How to profit from it (Luis Miguel Sánchez [2018](https://towardsdatascience.com/cryptocurrency-arbitrage-how-to-profit-from-it-e2d7bf805fde))
