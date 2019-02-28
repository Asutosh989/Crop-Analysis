# Crop-Analysis

### Aim:

Your team is working on building a variety of insight packs to measure key trends in the Agriculture sector in India. You are presented with a data set around Agriculture and your aim is to understand trends in APMC (Agricultural produce market committee)/mandi price & quantity arrival data for different commodities in Maharashtra.

### Objective:

- Test and filter outliers.
- Understand price fluctuations accounting the seasonal effect
    - Detect seasonality type (multiplicative or additive) for each cluster of APMC and commodities
    - De-seasonalise prices for each commodity and APMC according to the detected seasonality type
- Compare prices in APMC/Mandi with MSP(Minimum Support Price)- raw and deseasonalised
- Flag set of APMC/mandis and commodities with highest price fluctuation across different commodities in each relevant season, and year.

### How to use
1. Must have python 3.6+ and jupyter notebook
2. Clone the Repository with the following command
  `git clone https://github.com/Asutosh989/Crop-Analysis`
3. Move into the directory by typing
  `cd Crop-Analysis`
4. Create a virtual environment as
  `pipenv shell`
5. Install all dependencies by running the following command
  `pipenv install`
6. Open the folder in jupyter notebook in a default browser by running the command
  `jupyter notebook`
7. Open the Crop_Analysi.ipynb and done.

### Output files
We have got 4 output files to get some interesting insights of the data

1. **Price_fluctuation_throughout_year.csv**
    - This file give the insight of as how the price of the crops fluctuate throughout the year in the form of standard deviation.
    - Which crop's prices are affected by the months and which not.
  

2. **Price_fluctuation_season_wise.csv**
    - This file give the insight of as how the price of the crops fluctuates season wise.
    - Which crop's prices are affected in which season and not.
  

3. **Commodity_arrival_affected_month_wise.csv**
    - This file give the insight of as how the arrival (in quintals) of all the commodities (crops, fruits, vegetables, cattles, etc.) to the Mandis fluctuate throughout the year in form of Standard deviation. 
    - Which commodities's availability in Mandis are affected by the months and which not.


4. **Commodity_price_affected_month_wise.csv**
    - This file give the insight of as how the price of the commodities (crops, fruits, vegetables, cattles, etc.) fluctuates throughout the year.
    - Which commodities's prices are affected by the months and which not.
