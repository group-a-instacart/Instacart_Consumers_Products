# Instacart_Consumer_Habits
<!-- PROJECT SHIELDS -->
[![Build Status][build-shield]]()
[![Contributors][contributors-shield]]()
[![MIT License][license-shield]][license-url]





<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Problem Statement](#about-the-project)
  * [Abstract](#abstract)
  * [Built With](#built-with)
  * [Methods](#method)
* [Visualations](#visualizations)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## Problem Statement: 
In the effort to explore, define, and understand the favorable grocery consumer, the research project question asks: what behavioral independent variables (day an order is placed, time of day an order is placed, and what items are ordered) best predict grocery consumer?

### Abstract:
Instacart shopping data can be analyzed to determine key shopper characteristics and related traits pertaining to food and non-food product consumer shopping traits and order histories. An exploratory data analysis confirms most Instacart orders occur between 0800 and 1600 (8 AM and 6 PM, respectively). Product reorders occurred on average at or around 8 days after the original order was placed. The analysis was extended to review non-food items. The analysis explores order characteristics and shopping patterns that may potentially identify ideal Instacart shopping consumer behaviors.

### Built With:
* [R](https://www.r-project.org/)
* [Tableau](https://www.tableau.com/)
* [Excel](https://products.office.com/en-us/excel)

## Methods Used Tableau

![method](https://user-images.githubusercontent.com/39780478/54024051-6edf6e80-414b-11e9-9cfe-b1394eb9725a.JPG)
The “prior” orders were connected to orders dataset. Products id in “prior” table was connected to products database, and products database were described using aisles. To reduce the count of categories in analysis I decided to select non-food products. 

<!-- Visualizations -->
## Visualizations Tableau

![products](https://user-images.githubusercontent.com/39780478/54023231-46ef0b80-4149-11e9-9c7a-32777deb0b96.JPG)

This chart shows that cleaning products including cleaning products for home and body are the main categories of a non-food line. 
The second big category which can be found in list is body care with products for specific needs of women and men. Third big category 
which can be composed from Aisle variable is child care. 

![variety of products](https://user-images.githubusercontent.com/39780478/54023592-368b6080-414a-11e9-8765-93534341e0e3.JPG)

![histograms](https://user-images.githubusercontent.com/39780478/54023753-9550da00-414a-11e9-9e8f-e244c4ce99b0.JPG)
This histogram shows the day from prior order histograms by Aisles. It can be seen that baby accessories buying with 7 day frequency mainly. Products with 1-2 week cycle are cleaning products, body lotions, oral hygiene, soap, air fresher products, long life products cleaning products, oral hygiene, deodorants, famine care etc. have big frequency abjection in the end of histograms because they are long life products which do not require frequent re-ordering. 

## Code: Exploratory Data Analysis in R
install.packages("data.table")
install.packages("dplyr")
install.packages("ggplot2")
install.packages("knitr")
install.packages("stringr")
install.packages("DT")
 
library(data.table)
library(dplyr)
library(ggplot2)
library(knitr)
library(stringr)
library(DT)

3.4 million grocery orders from more than 200,000 Instacart users
each user provides between 4 and 100 of their orders, sequence of products purchased are in each order
data also provides the week and hour of day the order was placed, and a relative measure of time between orders.
 
Identify basic EDA and identify the ideal consumer based off behavior
import data
orders.csv : all grocery orders
products.csv : all products
order_products_train.csv - order_products_prior.csv: specify which products were purchased in each order.
order_products_prior.csv contains previous order contents for all customers. reordered' indicates that the customer has a previous order that contains the product. some orders will have no reordered items.
aisles.csv : different aisles
departments.csv : different product departments
 
## Visualizations R

![r1](https://user-images.githubusercontent.com/39780478/54025184-9e43aa80-414e-11e9-9f95-973e1d6fb37a.JPG)
![r4](https://user-images.githubusercontent.com/39780478/54025646-034bd000-4150-11e9-9e6a-80082f2e8e0e.JPG)
![r5](https://user-images.githubusercontent.com/39780478/54025651-047cfd00-4150-11e9-975b-5e7588118a81.JPG)

## Data

Stanley, J. (2017, May 2). The Instacart Online Grocery Shopping Dataset 2017 Data Descriptions. https://gist.github.com/jeremystan/c3b39d947d9b88b3ccff3147dbcf6c6b 


<!-- CONTRIBUTING -->
## Contributing

Team A: Data Visualization 

1. Margaret
2. Jodie
3. Will
4. Jason


<!-- ACKNOWLEDGEMENTS -->
## References
* Anesbury, Z., Nenycz-Thiel, M., Dawes, J., & Kennedy, R. (2016). How do shoppers behave online? An observational study of online grocery shopping. Journal of Consumer Behaviour, 15(3), 261-270. doi:10.1002/cb.1566

* Browne, M. (2018, June 26). Grocery shopping has a hold on consumers, study finds. Retrieved from                 https://www.supermarketnews.com/issues-trends/grocery-shopping-has-hold-consumers-study-finds Instacart. (2017, December 1).

* Fry, B. (2018, May 1). Visualizing Data. Retrieved from https://www.oreilly.com/library/view/visualizing-data/9780596514556/ch01.html

* Harris, P., Riley, F. D., Riley, D., & Hand, C. (2017). Online and store patronage: A typology of grocery shoppers. International Journal of Retail & Distribution Management, 45(4), 419-445. doi:10.1108/ijrdm-06-2016-0103

* Instacart. (2017, December 1). Instacart Help Center - What can we do for you? Retrieved from https://www.instacart.com/help/section/200758544
* Instacart. (2017). [The Instacart Online Grocery Shopping Dataset 2017]. Published raw data.Accessed from https://www.instacart.com/datasets/grocery-shopping-2017Pan, S., Giannikas, V., Han, Y., Grover-Silva, E., & Qiao, B. (2017). Using customer-related data to enhance e-grocery home delivery. Industrial Management & Data Systems, 117(9), 1917-1933.doi:10.1108/imds-10-2016-0432

* Stanley, J. (2016, February 17). Data Science at Instacart – tech-at-instacart. Retrieved from                                     https://tech.instacart.com/data-science-at-instacart-dabbd2d3f279

* Stanley, J. (2017, May 2). The Instacart Online Grocery Shopping Dataset 2017 Data Descriptions. Retrieved from https://gist.github.com/jeremystan/c3b39d947d9b88b3ccff3147dbcf6c6b





<!-- MARKDOWN LINKS & IMAGES -->
[build-shield]: https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat-square
[contributors-shield]: https://img.shields.io/badge/contributors-4-orange.svg?style=flat-square
[license-shield]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square
[license-url]: https://choosealicense.com/licenses/mit
[product-screenshot]: https://raw.githubusercontent.com/othneildrew/Best-README-Template/master/screenshot.png
