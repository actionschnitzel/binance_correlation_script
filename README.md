## binance_correlation_script

A jupyter notebook that calculates correlation matrices for crypto coins in binance exchange

This script will require a binance API key to run and will do the following

## dependencies
[Jupiter Nootbook](https://jupyter.org/install)
- pip install notebook    
## useage    
1. run:
```jupyter notebook```

2. in browser choose path to "auto_coin_list"

3. Follow the instructions

4. Cell > RUN ALL

5. Wait ca. 10 min to finish




  



**1.** Download binance coin data from coinlist

**2.** Produce correlation matrix for

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Raw Coin value** (1 minute intervals)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Detrended coin value** (first difference)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Detrended coin value** (rolling mean) 
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**rolling mean** itself

coded in Python 3.7

## auto_coin_list.ipynb

An automatic coin list generator that will scout binance for the most correlated trading pairs to a single starting coin. 
