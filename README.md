# California and United States Emissions and Energy Production

## Project Intro

Never on human history have seen all the changes happening on our Planet so fast. The answer of this changes is call climate change. A statement release by the Secretary of Defense
said that "It is a national security issue, and we must treat it as such." (Austin III).
To understand how climate change, we need to know what contributes to it and how can we start taking action to compensate our mistakes. According to NASA, Human activities (primarily the burning of fossil fuels) have fundamentally increased the concentration of greenhouse gases in Earth’s atmosphere, warming the planet.
The main gases that contributes to climate change are "Water vapor, Carbon dioxide (CO2), Methane, Nitrous oxide and Chlorofluorocarbons (CFCs)."("The Causes Of Climate Change")

So we asked ourselves, how is United States and California contributing to the emissions, specificly CO2, on the Energy Production and how is it changing to reach net zero emissions by 2050 as it is "the internationally agreed upon goal for mitigating global warming."("What Is Net Zero? - Net Zero Climate")

## Project Description

The goal of this project is to analyze and visualize all the data collected to represent the Renewable Energy in CA, Energy Production of US and CA and CO2 Emissions from CA and US from at least the last 10 years.

* Alternative Hypothesis: California has reduced CO2 emissions significaly and implemented a significally ammount of renewable energy sources.
* Null Hypothesis: California has not reduced CO2 emissions significaly and has not implemented a significally ammount of renewable energy sources.

## Summary
### Total Energy Consumption
* Energy Consumption has increased in the last decade (2010-2019) for California and US
![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/Total%20Energy%20Usage%20in%20CA%20from%202010%20to%202019.png)
![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/Total%20Energy%20Usage%20in%20US%20from%202010%20to%202019.png)
* Energy Consumption would increase in California by 11.6% and 12.772% for US by 2050
* California represent 8% of total US Energy Consumption and it is the second state after Texas (doubling CA Energy Consumption!)
![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/Energy%20Consumption%20in%20US%20on%202019.png)

### CA non-renewable and renewable energy production and emissions
* California has increased its renewable energy production from 35% of total prodcution to 42.84%
* By year 2026 California's renewable energy production should account for 59.54% of total energy production.

![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/ca_renew.png)
* CA has reduced its emissions from electrical power from 89.2 MMTCO2E to 58.8, a decrease of 34.08% from 2010-2019

![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/ca_renew_vs_non.png)
* CA total emissions acroos all sectors has declined from 443.7 MMTCO2E to 418.2, a decrease of 5.75% from 2010-2019

![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/ca_total_emissions.png)
![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/ca_emissions.png)

* CA emissions by 2026 should decrease by 22.28 MMTCO2E.

### US Power Source Energy Production
* Coal displayes the hihgest mean of 112,2274 Thousand Megawatthours, follow by Natural gas and Nuclear respectively.

![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/Box-Plot%20U.S.%20Energy%20Production%20Years%202010-2020.png)
### CA Power Plants
* California is the leading state on power plants compared to all other states.

![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/Number_of_PowerPlants_per_State.png)
* Constant amount of power plants over the years compared to the rest of the US.

![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/CA_Percents.png)
* California's energy production and usage is average compared to other states

![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/CAvsUSA_Percent_Utilized.png)
* California has been producing less energy, thus leading to less usage.

![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/Energy%20Generated_vs_Utilized.png)
### Conclusion
* Power plants do not represent a big percentage of total CO2 emissions on California.
* California is doing a great job switching to renewable energy
* Hopefully reaching 100% renewable energy production by 2045 as Governor Jerry Brown stated on the law passed on September 10th, 2018.
* If we want to reduce CO2 emissions to net zero, we need to invest and reduce emissions mainly from the transportation sector which corresponded to 39.71% of the total CO2 emissions whereas Power plants CO2 emissions only counted for 14.06% of the total.

![](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Images/ca_emissions_decrease.png)

## Libraries Required
* matplotlib
* pandas
* numpy
* scipy.stats
* os

## File Description
### Images
All png images created for this project
### Resources
* [Net_generation_for_electric_power.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/Net_generation_for_electric_power.csv)
* [ca_emissions.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/ca_emissions.csv)
* [ca_energy_gen.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/ca_energy_gen.csv)
* [use_tot_realgdp.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/tree/main/Resources#:~:text=1%20hour%20ago-,use_tot_realgdp.csv,-Merging%20and%20cleaning)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2010.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2010.csv)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2011.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2011.csv)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2012.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2012.csv)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2013.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2013.csv)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2014.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2014.csv)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2015.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2015.csv)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2016.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2016.csv)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2017.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2017.csv)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2018.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2018.csv)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2019.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2019.csv)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2020.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/List_of_plants_for_all_fuels_United_States_all_sectors_2020.csv)
* [plants.csv](https://github.com/DylanRCastillo/CA-US-Emissions-and-Energy-Production/blob/main/Resources/plants.csv)

#### Websites for DataSets
* [Net_generation_for_electric_power.csv](https://www.eia.gov/electricity/monthly/)
* [ca_emissions.csv](https://www.energy.ca.gov/data-reports/energy-almanac/california-electricity-data/california-electrical-energy-generation)
* [ca_energy_gen.csv](https://www.energy.ca.gov/data-reports/energy-almanac/california-electricity-data/california-electrical-energy-generation)
* [use_tot_realgdp.csv](https://www.eia.gov/state/seds/seds-data-complete.php?sid=CA#StatisticsIndicators)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2010.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2011.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2012.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2013.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2014.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2015.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2016.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2017.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2018.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2019.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [List_of_plants_for_all_fuels_United_States_all_sectors_2020.csv](https://www.eia.gov/electricity/data/browser/#/topic/1?agg=2,0,1&fuel=vtvv&geo=000000000004&sec=008&freq=M&datecode=201206&rtype=s&pin=&rse=0&maptype=0&ltype=pin&ctype=linechart&end=202106&start=200101)
* [plants.csv](https://www.kaggle.com/la-times/california-electricity-capacity)

## Reference
* Austin III, Lloyd J. "Statement By Secretary Of Defense Lloyd J. Austin III On Tackling The Climate Crisis At Ho". U.S. Department Of Defense, 2021, https://www.defense.gov/News/Releases/Release/Article/2484504/statement-by-secretary-of-defense-lloyd-j-austin-iii-on-tackling-the-climate-cr/.
* "The Causes Of Climate Change". Climate Change: Vital Signs Of The Planet, 2021, https://climate.nasa.gov/causes/.
* "What Is Net Zero? - Net Zero Climate". Net Zero Climate, 2021, https://netzeroclimate.org/what-is-net-zero/.
