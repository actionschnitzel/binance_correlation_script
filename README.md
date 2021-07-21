## binance_correlation_script

A jupyter notebook that calculates correlation matrices for crypto coins in binance exchange

This script will require a binance API key to run and will do the following

## dependencies
python-binance==0.7.9
datetime
matplotlib==3.3.1
numpy==1.19.1
pandas==1.2.4
seaborn==0.11.1


[Jupiter Nootbook](https://jupyter.org/install)    
 ```pip install notebook```        
## useage    
1. run:
```jupyter notebook```

2. in browser choose path to "auto_coin_list" (when you type "jupiter notebook" in terminal or CMD it opens a Browser tab, from where you can access the auto_coin_list.ipynb
    
2.1 click on binance_correlation_script >  auto_coin_list.ipynb and thats it

3. Follow the instructions

4. Cell > RUN ALL

5. Wait ca. 10 min to finish


****

  



**1.** Download binance coin data from coinlist

**2.** Produce correlation matrix for

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Raw Coin value** (1 minute intervals)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Detrended coin value** (first difference)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Detrended coin value** (rolling mean) 
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**rolling mean** itself

coded in Python 3.7

## auto_coin_list.ipynb

An automatic coin list generator that will scout binance for the most correlated trading pairs to a single starting coin. 
