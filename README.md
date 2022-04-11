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
## Scrap Notebook
I included this here  because oftentimes I like to work things out in a separate notebook. While going through the assignment I had some questions and I wanted to look into in my scrap notebook. Namely I wanted to know:
> 1. Could we have concatenated both dataframes into one dataframe and calculated the arbitrate spread (and other calculations of course) in our  dataframe and then plotted
> 2. I wanted to see if I can created a histogram that could show  the distribution of dates with an arbitrafe spread greater than zero. I think while `describe()` is good there are other things we can learn from looking at the our dataset on a whole

When i return to my projects I tend to look at my scrap notbook first to see what I was thinking and what else i discovered in my exploration to solve the issues I came up with.
## Discussion
This is an interesting article about arbitrage of cryptocurrencies that helped to contextualize this coding effort:

**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data Science and Cryptocurrency arbitrage: How to profit from it (Luis Miguel Sánchez [2018](https://towardsdatascience.com/cryptocurrency-arbitrage-how-to-profit-from-it-e2d7bf805fde))

Thought this t=ype of arbitrage  I am sure doesnt exist currently, I am sure there are other opportunities for arbitrage that exists within the crypto ecosystem. Just like how arbitrage traders enhance the efficiency of the financial markets, they would do the same within cryptocurrencies. There are various coins with  diffent market caps associated and price differences between similar assets currently exist. The lower-priced cryptos (ADA,SOL, for example)  are already being bid up while higher -priced cryptos are sold off. Aside from staking I see arbitrafe as a way of addressing inefficiencies in the crypto market’s pricing in part by adding liquidity. However this seems a task for a larger organization that can buy adn sell in volume. They have diffferent agency and capacity thank the average retails investor that may seek to stake some of their currencies or hold for years at a time/.



