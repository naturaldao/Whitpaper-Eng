# 3. Issurance of Decentralized Benchmark Token

Issued by ETH FORGING model, NDAO will temporarily has a strong relationship with ETH's US dollar price, which means 1 NDAO is equal to 1 US dollar. Its demicals are 18. By the time that NaturalDAO has pricing power, the price of NDAO will no longer have anything to do with US Dollar. NDAO's issuance mechanism is as follows:

1. We introduce a Reverse Improved CPMM algorithm to initialize the issuance system with ETH's circulating supply, and market cap.
2. ETH's circulating supply the first day NDAO issured will be used as initial ETH supply.
3. On system initialization there are no real NDAOs, and ETH's real-time market cap \(US dollar\) will be used as the system's initial and virtual NDAO supply.
4. After an ETH supply and an NDAO supply are obtained the product \(liquidity\) of the two crypto supplies can be composed.
5. When a user buys NDAOs with ETHs the product's ETH supply will decrease rather than increase, and the product's NDAO supply will increase rather than decrease. For instance, if the product's ETH supply is 107,477,373 and after a user buys NDAOs with 100 ETHs the ETH supply will be 107,477,273 and the ETH's price in the system will rise according to the algorithm.
6. This issurance of NDAO is done by smart contracts. It is what we call an "ETH forging model" i.e. using ETH to generate NDAO. On system initialization there are no real NDAOs but we make a virtual NDAO supply. Once ETH is sold to this system NDAO will be generated.
7. The product's ETH supply and NDAO supply will be updated on a daily basis.
8. ETH's price in the system is calculated this way: firstly we get a price "x" by using the ICPMM, secondly we take the real-time price "y" from coinmarketcap.com, and get a final price by combining a weighted "x" and weighted "y".

x = Price of Reverse Imporved CPMM

y = Price of Coinmarketcap

N = Volume of ETH in the last 24 hours of NaturalDAO

C = Volume of ETH in the last 24 hours of Coinmarketcap

a = N / \(N+C\)

b = C / \(N+C\)

ETH Price = \[ x \* a + y \* b \]

During a market collapse if ETH's market cap dramatically shrinks the product's NDAO supply will decrease accordingly.

1. When the trading volume of ETH in NaturalDAO exceeds twice the volume in Coinbase, or four times the volume in Poloniex, or the volume in the exchange ranked 100th in Coinmarketcap's ethereum markets for 30 consecutive calendar days, NaturalDAO will remove all elements obtained from outside markets and determine the ETH's price by using only the ICPMM. These trigger conditions are defined for NaturalDAO to eventually eliminate influences from centralized markets.
2. Initially in NatualDAO ETH's price, as well as product's NDAO supply will be heavily influenced by centralized markets. The ICPMM may play a less effective role for a relatively long time. NaturalDAO will proceed based on markets and trading activities, and we will not intervene in its change.

