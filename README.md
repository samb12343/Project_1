# Project 1

![HeaderPicture](BlockchainHeader.png)

# <p align="center"> Blockchain in Oil and gas </p>
  <p align="center"> How has the utlization of blockchain replacing traditional ledgers and contracts effected the oil and gas industry? </p>
  
## Basis
I've been hired by a small oil company to see the benefits of integrating blockchain into the company software replacing their ledger and use of contracts to see if they should utilize this "new" technology.

Blockchain is a new technology that is barely a decade old (although founded in 1991, it was not used until 2009). The possibilities of what the technology can do is still unknown as industries are slowly implementing the technology. Currently, what attracts industries to the technology is the decentralized ledger and smart contract system it offers. In the oil industry,this cuts out time spent on waiting on both parties to get back with each other when both of their sides of the contract are fullfilled before drilling for oil. The goal of this technology is to cut time wasted (workers not drilling, being forced to stand around waiting for the next drill to happen costing the companies to pay for wasted hours due to the long process of both parties communicating with each other).

I created collected and cleaned the data displaying the cut of costs through the implementation of blockchain.

## Data

I've collected and cleaned the data from multiple sources specifically their financial reports. I have cleaned all the data into a single .csv file.

**Data Includes**
| Date  | Type of Data  |
| ------------- | ------------- |
|1920-Present |Crude Oil Production |
| 2017-Present |  Operational Costs  |
| 2017-Present | Cost of Revenue  |
| 2017-Present | Total Expenses |

**Potential Data Issues**

* Since the technology is so new, a majority of oil companies begain using the blockchain technology in 2019 and politics due to a change in president meaning new regulations. This results in only focusing on the year 2019-2020.


Finalized Data: [Chevron and ExxonMobil Financial Statements](Finalized_Data.csv) &
                [Crude Oil Production](Crude_Oil_Production.csv)

## Procedure

* The official financial statements were provided by Chevron and ExxonMobil via PDF. The PDFs were downloaded and put into an excel spreadsheet. This was used to determine their expenses over the years.
* The API from Yahoo Finance was used to pull additional Chevron and ExxonMobil finanical statement information not found in their reports on their website. This was used to determine their expenses over the years and to see when the companies began implementing blockchain replacing their ledgers and contract system.
* The API from U.S. Energy Information Administration was pulled in order to get the number of crude oil production in the United States. This was used to determine if the amount of crude oil production could be correlated the lowered expenses besides blockchain.

## Analysis

It is extremely important to remember the following:
* Blockchain is a new technology.
* Chevron and ExxonMobil began using it 2019.
* The primary goal was to cut expenses (replacing human middlemen with automation specifically smart contracts).
* COVID-19
* The election of a new president in 2020 resulting in new regulations.

Blockchain has proven to be an effective technology in cutting expenses by replacing human middlemen with automation. The less time required to wait on the response from another party results in more drill time equating to more oil production. With more time required to wait on the response from another party, companies are wasting paid hours on their labor force ultimately a problem they face on a large scale. 

CHEVRON
| Breakdown  | TTM | 2019-2020 | 2018-2019 | 2017-2018 |
| ------------- | ------------- |---| --- | --- | 
|Operational Costs| 30,736,000 USD |30,572,000 USD |30,459,000 USD |37,080,000 USD |
|Cost of Revenue | 72,053,000 USD | 69,996,000 USD | 109,331,000 USD |95,114,00 USD |
|Total Expenses | 102,789,000 USD |139,765,000 USD |144,456,000 USD | 132,194,00 USD |

EXXONMOBIL
| Breakdown  | TTM | 2019-2020 | 2018-2019 | 2017-2018 |
| ------------- | ------------- |---| --- | --- | 
|Operational Costs| 37,575,000 USD |43,192,000 USD |45,609,000 USD |42,850,000 USD |
|Cost of Revenue | 169,915,000 USD | 199,625,000 USD | 211,599,000 USD |182,238,000 USD |
|Total Expenses | 207,043,000 USD |242,817,000 USD |257,208,000 USD | 1225,088,000 USD |
