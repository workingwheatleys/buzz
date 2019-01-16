+++
author = "Keri Wheatley"
categories = ["modeling","data science"]
tags = ["forecasting","pyton"]
date = "2019-01-14"
description = "How to forecast demand using Python"
featured = ""
featuredalt = "Bikes clipart"
featuredpath = "date"
linktitle = ""
title = "Kaggle Bike Sharing Demand"
type = "post"

+++

A public bicycle-sharing system is a service in which bicycles are made available for a shared use to individuals on a very short-term basis. A bike-sharing system is comprised of a network of kiosks throughout a city which allows a participant to check-out a bike at one location and return it to a different location. Participants of a bike-sharing system can rent bikes on an as-needed basis and are charged for the duration of rental. Most programs require participants to register as users prior to usage. As of December 2016, roughly 1000 cities worldwide have bike-sharing systems.

Bike-sharing kiosks act as sensor networks for recording customer demand and usage patterns. For each bike rental, data is recorded for departure location, arrival location, duration of travel, and time elapsed. This data has valuable potential to researchers for studying mobility within a city. On a more practical level, being able to predict demand is essential for the company that is renting out the bicycles. A kiosk that runs out of bicycles translates directly to lost revenue, so it is important to know how many bicycles will be needed.

For this project, we explore customer mobility in relationship to these factors:

Time of day
Day type (workday, weekend, holiday, etc.)
Season (Spring, Summer, Fall, Winter)
Weather (clear, cloudy, rain, fog, snowfall, etc.)
Temperature (actual, “feels like”)
Humidity
Windspeed
This project explores changes in demand given changes in weather and day. Our project delivers an exploratory data analysis as well as a machine-learning model to forecast bike rental demand. Bike rental demand is measured by total rental count which is further broken down into two rental types: rentals by registered users and rentals by non-registered users.

This Kaggle competitions is scored on the Root Mean Squared Error (RMSE) of the predictions. Therefore, our task is to predict the total rider counts for the testing set that resulted in the lowest RMSE.