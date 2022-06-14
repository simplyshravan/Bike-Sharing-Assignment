# Bike Sharing Assignment
> Boom Bikes have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contributors](#contributors)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- The company wants to know:
* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Technologies Used
- Python Pandas - version 1.1.5
- Python Numpy - version 1.19.5
- Python Seaborn - version 0.11.2
- Jupyter Notebook - version 6.4.10
- ipykernel - version 6.13.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Conclusions
Below are 3 attributes which highly affect the demand of shared bikes.
1.	atemp: feeling temperature in Celsius. With one unit increase in atemp , the demand of bikes will increase by 0.36.
2.	weathersit: Weather has negative impact on demand of bikes specially for below 2.
    - Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    - Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered cloud
3.	yr: year has positive correlation demand of bikes.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contributors
* [Shravan](https://github.com/simplyshravan)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
