# Segments Quiz: Overview #

## About This Project ##

### Problem Space ###

Projects built in flash are difficult to update and maintain due to limited code accessibility, and very expensive licensing/development fees. Adobe announced recently that it will completely seize all support and distrubition of Flash come 2020.

### Our Goal ###

Re-create the Flash version using resources that cut third-party maintenance costs by making it accessible and easy to update regularly, without sacrificing any of its original functionality. 

### Our Solution ###

Using JavaScript (jQuery, AJAX, Chart.js) and HTML/CSS, data is read from dynamic JSON files and elements of the quiz are generated from this data.

The implementation of external JSON files allows for an easier updating process, as the quiz components (questions, graphs, result page information, etc.) can be changed without the need to go directly into the source code. Character strings and values can be altered and added/removed in the user-intuitive JSON files, and the source code will then parse the objects into the variables used to build the dynamic elements.

## About This Quiz ##

This questionnaire was designed to help industrious people choose a business direction that will meet their needs, by matching their financial situation to the profile of one of five industry portfolios:

**Collect**

**Stock**

**Reserve**

**Cache**

**Amass**
