# Pandas Challenge - Heroes of Pymoli

Heroes of Pymoli is a study about a fictional mobile game. The data is manipulated to show the relationship between how much and how often different subsets of players are spending on the game.In this project, I used Python, Jupyter Notebook, and the Pandas library to analyze user data for a video game company. I used I analyzed data of in-game purchases by players. I aggregated and analyze the data to view trends in the purchasing behavior of the players.

* [Background](#background)
* [Observable Trends Based on the Data](#trends)
* [Jupyter Notebook](#nb)
* [Technologies Used](#technologies)

##  <a name="background"></a>Background

For this project, I started with csv file. This file can be found [here](./HerosOfPymoli/Resources). One [csv file](./HerosOfPymoli/Resources/purchase_data.csv) includes information about the video game company purchase data.

## <a name="trends"></a>Observable Trends Based on the Data

These were the key insights I found in my analysis:

  *Most of the players were male.

  *The 20-24 age group made most of the purchases in the game.

  *Listed five most profitable items. I used basic Pandas methods and functions to do my analysis.

Final Report includes:

 *Player Count
	*Total Number of Players

 *Purchasing Analysis (Total)
	*Number of Unique Items
	*Average Purchase Price
	*Total Number of Purchases
	*Total Revenue
 *Gender Demographics
	*Percentage and Count of Male Players
	*Percentage and Count of Female Players
	*Percentage and Count of Other / Non-Disclosed
 
 *Purchasing Analysis (Gender)
  The below each broken by gender
	*Purchase Count
	*Average Purchase Price
	*Total Purchase Value
	*Average Purchase Total per Person by Gender
	
 *Age Demographics
  The below each broken into bins of years (i.e. 0-10, 10-14, 15-19, etc.)
	*Purchase Count
	*Average Purchase Price
	*Total Purchase Value
	*Average Purchase Total per Person by Age Group
	
 *Top Spenders
 The top 5 spenders in the game by total purchase value, then list (in a table):
	*SN
	*Purchase Count
	*Average Purchase Price
	*Total Purchase Value

 *Most Popular Items
  The 5 most popular items by purchase count, then list (in a table):
	*Item ID
	*Item Name
	*Purchase Count
	*Item Price
	*Total Purchase Value

 *Most Profitable Items
 The 5 most profitable items by total purchase value, then list (in a table):
	*Item ID
	*Item Name
	*Purchase Count
	*Item Price
	*Total Purchase Value


##  <a name="nb"></a>Jupyter Notebook

For this project, I used jupyter notebook to render and display the results of this analysis. You can view the notebook here:

<https://github.com/PunamSonawane/Pandas-Challenge/blob/master/HerosOfPymoli/HeroesOfPymoli_Main.ipynb>

The notebook is also available inside this repository [here](./HerosOfPymoli/HeroesOfPymoli_Main.ipynb).

##  <a name="technologies"></a>Technologies Used

* Python
* Pandas library
* Jupyter Notebook