# Sumo Easy Miner

Copyright (c) 2017, Sumokoin.org

The most easy, intuitive CPU miner for cryptonote-based cryptocurrencies like SUMOKOIN (SUMO), Monero (XMR), Aeon (AEON) etc.

![](http://www.sumokoin.org/images/easy-miner-features_1080x1100.png)

** Dependencies **

1. Python
2. Python PySide library: `sudo apt-get install python-pyside`
3. Python PsUtil library: `sudo apt-get install python-psutil`

** USAGE **

1. Clone the repo:
		
		git clone https://github.com/sumoprojects/SumoEasyMiner SumoEasyMiner

2. Build cryptonight hashing library from [cryptonight-hash-lib](https://github.com/sumoprojects/cryptonight-hash-lib) and put it to `libs` sub-directory. You need to copy the `.so` file generated by the build.

3. Run the miner:
		
		python sumominer.py
