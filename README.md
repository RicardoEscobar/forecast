# Forecast
## Description
In this project you'll use click events to help a weather service app display hourly forecasts.

## Objective
Forecast is building a weather service that displays a five-day forecast. [Here's what it looks like]("https://s3.amazonaws.com/codecademy-content/projects/2/forecast/index.html"). When a weekday is clicked, an hourly forecast of the day is shown.

## Tasks
### 1.
Look at __index.html__:

In `<div class="main">`, there are five `<div class="day">` elements containing information about each day.

Inside each `.day` div, there is a `<span class="glyphicon glyphicon-plus"></span>` element. This defines the plus sign (+) next to each weekday name.

Following each `.day` div, there is a `<div class="hourly">` element containing the hourly forecast of a day.

### 2.
In __script.js__, add a click event handler to the `.day` divs.

### 3.
When a `.day` div is clicked, toggle the following `.hourly` div, which is its next sibling.

### 4.
When a `.day` div is clicked, change the `<span class="glyphicon glyphicon-plus"></span>` element to be a minus sign by toggling the class `glyphicon-minus`. Use `.find()` the `<span>` element inside the `.weekday` div.
