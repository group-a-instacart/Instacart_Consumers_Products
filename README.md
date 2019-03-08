# Instacart_Consumer_Habits
<!-- PROJECT SHIELDS -->
[![Build Status][build-shield]]()
[![Contributors][contributors-shield]]()
[![MIT License][license-shield]][license-url]




<!-- PROJECT LOGO -->
What Is Instacart
![instacart_what_is](https://user-images.githubusercontent.com/39780478/54022540-90d6f200-4147-11e9-922f-38c9225ad1ca.JPG)"
  

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

## Method
![method](https://user-images.githubusercontent.com/39780478/54022968-97199e00-4148-11e9-8035-aae7ca393825.JPG)
The “prior” orders were connected to orders dataset. Products id in “prior” table was connected to products database, and products database were described using aisles. To reduce the count of categories in analysis I decided to select non-food products. 

<!-- Visualizations -->
## Visualizations

![products](https://user-images.githubusercontent.com/39780478/54023231-46ef0b80-4149-11e9-9c7a-32777deb0b96.JPG)
This chart shows that cleaning products including cleaning products for home and body are the main categories of a non-food line. The second big category which can be found in list is body care with products for specific needs of women and men. Third big category which can be composed from Aisle variable is child care. 

![variety of products](https://user-images.githubusercontent.com/39780478/54023592-368b6080-414a-11e9-8765-93534341e0e3.JPG)

![boxplot](https://user-images.githubusercontent.com/39780478/54023429-caa8f800-4149-11e9-94b0-b89494987d2f.JPG)
This chart sorted by Average Cart Order. It can be seen that first what people ordered in Cart is spirits but from other point of view the spirits are 3-rd (median) cart in order. This may means that people who buy spirits buy a limited list of goods. Same with facial care. This information could be used by service to place the categories in right list on screen of customers in relation to frequency of orders first of course. 

![histograms](https://user-images.githubusercontent.com/39780478/54023753-9550da00-414a-11e9-9e8f-e244c4ce99b0.JPG)
This histogram shows the day from prior order histograms by Aisles. It can be seen that baby accessories buying with 7 day frequency mainly. Products with 1-2 week cycle are cleaning products, body lotions, oral hygiene, soap, air fresher products, long life products cleaning products, oral hygiene, deodorants, famine care etc. have big frequency abjection in the end of histograms because they are long life products which do not require frequent re-ordering. 

### Installation



<!-- USAGE EXAMPLES -->
## Usage

Use fgdfg to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)





<!-- MARKDOWN LINKS & IMAGES -->
[build-shield]: https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat-square
[contributors-shield]: https://img.shields.io/badge/contributors-1-orange.svg?style=flat-square
[license-shield]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square
[license-url]: https://choosealicense.com/licenses/mit
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: https://raw.githubusercontent.com/othneildrew/Best-README-Template/master/screenshot.png
