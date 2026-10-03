# Wildfire emissions prediction project

## Introduction
With climate change as a global threat to humanity and the dangers constantly worsening, it is vital that we use modern technology to track the damage we are doing to our planet so that we can formulate plans on how to slow it down.

## Motivation
Following the drought in the UK during the 2026 summer and after seeing the rise in wildfires across Europe, I wanted to build a project to allow us to track the damage of these wildfires.

## My process
I started by exploring a question I had: is it possible to know if a wildfire was caused naturally (through a lightning strike) or caused by a human?

To do this I began making a logistic regression model using publicly accessible data on wildfires across the world, using factors such as weather metrics and climate zones to predict human causation.
My work on this is found in wildfire_causation.ipynb (although it is still a work in progress)

After facing difficulty on creating this as I was learning all the technology from scratch, I decided to temporarily pivot to a different question: is it possible to predict co2 emissions from a given wildfire?

This time I took more time to thoroughly explore the data using analysis to be sure that the linear regression model I would be using would definitely create an accurate prediction. The work for this in co2_prediction.ipynb.
