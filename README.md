# Corruption-analysis-Gos-zakupki

This paper analyses and investigates the effect of corruption on competition in procurement in Russia. Russian context is no different from the rest of the world and it order to understand consequences of corruption there it is enough to recall the scandal concerning embezzlement of 256 billion rubles from the state budget during the construction of the Moscow Ring Road for which no one has been held responsible for so far. 

Russian public procurement corresponds to 6.8 trillion rubles  and is roughly 8% of GDP for 2018. Majority of given contracts are conducted through actions. In order to monitor activity and reduce probability of corruption government uses regulation (Federal law №44 which was imposed in 2013 right after Federal law №94 (2005)). According to given regulation public must be given all procurement information thus all procurement auctions above hundred thousand rubles must be conducted through similar competitive procedure and all the information concerning the matter of an auction, its timeline, number of bidders, winning firm and a starting price is published on specific (and centralized for whole Russia) website which is going to be used during the analysis in a given paper . Moreover, electronic bidding system is being implemented during last few years and one of the recent legislative changes made was forcing almost all types of procurements to be conducted in an electronic form.

The model
As a result, the following analysis focuses on the following variables:
-	Relative price change between two best bids (used as dependent variable corresponding to presence of corruption since price change <1% should indicate of a corruptive pattern)
-	Number of bidders (should decline probability of corruption due to increased competition)
-	Reserve price (more expensive auctions are more likely to be more corruptive due to bigger rent-seeking opportunities)
-	Duration of an auction (corruption is more likely to be present in shorter auctions since if auctioneer and bidder collude prior to the start of auction, there is no incentive for auctioneer to extend the duration of tender)
-	Timing of bids
-	Position of winning bid in time

If corruption is present, there should be big share of auctions with small relative price change and winner placing bid last and late
The model estimates the following relationship:

Estimated coefficients are presented in Figure 7. It can be seen that all variables are significant and there exists positive dependence of suggested corruptive patterns 〖(winner last〗_i*〖last moment bid〗_i) on price change being less than 1% (〖suspect price change〗_i). Moreover, reserve price also positively impacts dependent variable, whereas increase in number of bidders tends to negatively impact corruption pattern.![image](https://user-images.githubusercontent.com/79480062/115113266-2a616680-9f92-11eb-9bf7-765bb0c70986.png)

![image](https://user-images.githubusercontent.com/79480062/115113274-30efde00-9f92-11eb-9e55-7583b13ca13f.png)


<img src="https://user-images.githubusercontent.com/79480062/115112948-7f03e200-9f90-11eb-97ae-cecf4548f255.png" alt="alt text"  width="700">

<img src="https://user-images.githubusercontent.com/79480062/115112928-60055000-9f90-11eb-960f-d33517e010ad.png" alt="alt text" width="500" height="440">


Conclusion 

Following research paper makes an attempt to analyze corruption patterns in sealed-bid public procurement auctions in Moscow. It proposes several corruptive patterns which may occur in this type of auctions: timing of bids and price variations across two best bidders are the variables of interest. Using publicly available data archive on 2014-2019 years and provides empirical estimates of this variables via OLS. Obtained results satisfy proposed hypotheses of presence of corruptive patterns in given data.

All auction data can be downloaded usingg this instruction:
https://zakupki.gov.ru/epz/main/public/download/downloadDocument.html?id=10217
