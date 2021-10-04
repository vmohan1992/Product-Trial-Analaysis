# Product-Trial-Analysis

This notebook encomapsses data cleaning & peprepation of a product_trial data , particularly using pandas library. that can be used for further downstream analaysis.


## Method

a. Pull the trial_data\
b. Replace all the null values in channels with 0\
c. add the column active_trial which is defined as client having at least 1 channel\
d. Create a region column and categorise the client in following regions\
  i. United States/ Canada/Mexico - North America\
  ii. Ireland/United Kingdom - UK/Ireland\
  iii. France/Germany/Italy/Spain - EU Main\
  iv. Other countries - ROW\
e. Export the newly updated table into a CSV/Excel\

## Implementation


Download and save the data in the working directory
Clone the [repository](https://github.com/vmohan1992/Product-Trial-Analaysis)  using Git
Open the .ipynb filte in the IDE
Run the code
