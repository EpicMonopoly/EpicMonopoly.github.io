---
title: Rules
permalink: /docs/rule/
---

## Start up
    Every enterpriser will $1500 as initial cash, or the initial cash is determined by the difficulty of the game, or player can set custom configuration.

## Map
	Map consists of 40 spots, including start point, jail, in jail/just visiting, free parking, three chance spots, three society chests, income tax, luxury tax, twenty-two real-estates grouped by eight blocks, four stations, two public utilities.
	For every 5 turns of game, the system will autonomy change the relative position of the real-estates, stations, public utilities.

## Economic factor(EF)
	For every 5 turns, the system will generate EF randomly.
	The range of EF depends on the difficult of the game. For easy model, the EF will change between -5% and 5%. For the normal one, it will change between -10% and 10%. For the hard model, EF will fluctuate between -15% and 15%.

## Alliance and Country
	There are two alliances, Asia, America & Europe. They have four countries respective.
	Asia: China, Japan, India, Russia
	America & Europe: United States, Canada, United Kingdom, German.

    If an enterprise enters a spot which own by his/her alliance, the owner should charge 90% of original value. If the number of countries of two alliances is different, the larger alliance owner should charge 92% of original value.

## Enterprisers
	The number of enterprisers are 2 to 6. When the enterprisers are less than 6, new enterprisers can enter the game if all the enterprisers agree.
	When the number of real-estate is less than 50%, new entrance policy is abandon.
	The new enterprisers’ initial cash depends on original initial cash and the largest amount of toal money enterprisers get from “Start Spot” so far. For example, the initial cash is $1500, the largest amount of total money got from “Start Spot” is $600, so the enterpriser will get $2100.

## Difficulty
### Easy
		Initial cash is $2000, the fluctuation of EF less than 5%. The original bonus when passing by “Start Spot” is $250. The number of house and hotel are no limited.
### Normal
		Initial cash is $1500, the fluctuation of EF less than 10%. The original bonus when passing by “Start Spot” is $200. The number of house and hotel are 32 and 12 respective.
### Hard
		Initial cash is $1000, the fluctuation of EF less than 15%. The original bonus when passing by “Start Spot” is $150. The number of house and hotel are 26 and 8 respective.

## Chance $ Society Chest
	The bonus and punishment of chance and society chest based on its original value and economic factor EF. New Value = Value * (1 + EF%).

## Roll a dice
	Every time roll two dices, when they come same for three time, he/she will directly go into prison.

## Real-estate
	When enterpriser step foot in unmanned real-estate spot, the enterpriser can chose do not buy it. And the spot will get into auction process.
	The cash in bank is unlimited, but the number of house and hotel is limited. (32 house and 12 hotel)
### The calculation for the value of eight color blocks:
    The value depends on the value of last turn and the current EF. Randomly sort the eight color blocks, for the first one, it will raise EF + 4%, for the second one, it will increase EF + 3%. As this process calculate all the real-estate value.
	The value of stations and utilities is same as real-estate.


## House and hotel
    If a player has all the same color houses and which are not mortgaged, she/he can build houses and hotels before or after dicing.
    The house must be built on the land in the same group where there are less houses, that is to say, the houses should be built homogeneously. 
    Do not build houses on the mortgaged land.
    When each the land belongs to the player has be build four houses, the player can choose to build a hotel.
    The player can build a hotel on the same land at the most.
    The player can build more than one houses in the same time, until can build a hotel, but also has to obey the homogeneous rule (one hotel regards as 5 houses).
    When there are multiple players who want to build a house at the same time, and the bank does not have enough houses, the bank will have to sell the house one by one and the player who charges the highest price will the house.
    The cost of building the house and the hotel is related to the cost of the previous round cost V and the economic impact factor X, the specific cost is V * (1 + X %).

## Rent calculation
    The base amount of rent will fluctuate according to the real estate price. The rent per player is related to the number of rentals paid for the real estate, and it will be recomputed after change hands. The specific calculation method is that the rent base amount is V, the rent amount is N, and the rent is V * (1 - (10 * N) %). That's 10% less per pay.

## Cashing
    The player can sell to the bank at 50% of the value of the house, and still keep the same number of houses on average, which is to say, the land that sells the most houses. The value of the house is the construction cost of the current house.
    A hotel is worth about five houses and can be sold separately.
    Players can mortgage lands to the bank in exchange for 50 percent of their current value, and the land to be mortgaged has no construction. The mortgaged ground cannot be rented, but the player still has the land title.
    The player can redeem the land before any player rolls the dice, except for the extra round when she/he throws the same number. The redemption price is 10% of the mortgage price, round off the decimal place.

## Transactions
    Transactions are subject to a 10% transaction tax on items/cards/money.
    At any time, the player can trade lands with his opponent where there is no construction, first deal will be accepted first.
    No lending between players.
    After the land has been mortgaged, the new owner can choose to redeem the land immediately, or not redeem immediately and just pays the transaction tax to the bank.  If you do not redeem it immediately, you will have to pay the extra mortgage charge.
    Bail cards can be traded. The bail card value is the current bail amount.

## Jail
    You can still rent, build a house or trade in prison, but you can't move.
    In prison, a player can choose to get out of jail by using a prison pass or bail before he rolls.
    When in prison, the player can be thrown (out of jail) when she/he rolls the same number dices, and there will be no extra rounds.
    When the same points are not thrown in the third round, the player will be released on bail and will be moved as he threw before.

## The calculation of bail
    The amount of bail is increased with the number of times in prison. The basic bail is 50 yuan. The bail is increased by 50% each time, round off the decimal place.

## Tax revenue
    Taxes are mainly made up of individual income tax and huge sum tax revenues.
 
## Income tax
    Individual income tax is divided into different grades according to the player's cash, and the proportion of each grade is different. And the tax ratio P is related to economic factor X. The final proportion is P(cur) = P(last) + (X/ 2).

## Luxury tax
    The huge sum tax is related to the total assets of the players, according to the total assets of the players. And the tax rate is up 2% every five rounds.
    All tax creditors are banks.
    Tax standards vary from country to country.

## Bankrupt
    Players declare bankruptcy if they do not have enough cash to pay their debts after selling or mortgaging their assets. When all the assets are transferred directly to the creditor, when the mortgaged land is transferred to the creditor, the principal hast to pays the transaction tax of 10% of the value immediately.
    If the creditor is a bank, the bank will auction off all the land at once with no reserve price.
    If you have multiple creditors (if you have to pay $50 to another player), the bank repays the debt and immediately auctions off all the land.

## Victory conditions
    The last player who does not go bankrupt.
    At the end of the time limit, the player who has the highest of the total assets is victorious.

