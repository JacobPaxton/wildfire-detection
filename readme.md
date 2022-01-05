# Wildfire Detection
Wildfires in America cause hundreds of millions or even billions of dollars in damages each year. Early detection is critical to containing these wildfires. NASA has deployed special monitoring satellites that use infrared technology to scan for wildfires and meteorologists use this data to provide minute-by-minute information on wildfire status. 

# Overview
This is a long-term project that I intend to work on in the background of other things. The industry for wildfire detection is massive and highly-dedicated. I want to build a small-scale solution that mimics the industry cycle for imagery collection, analysis, prediction, and alerting. 

# Plan
For this project, I want to do several things:
1. Leverage deep-learning image classification for pictures with wildfires
2. Use the GIS suite to build wildfire zone maps
3. Build a Tableau dashboard for this information
4. Push imagery to a cloud database that repeats in a cyclical fashion
5. Link the dashboard to the simulated-updating feed of imagery
6. Put a model into production that analyzes the imagery

In addition to the above project steps, I intend to go through the standard preparation and analytic steps to deliver insights and a predictive model.

# Progress
1. Decided to use Google Colab for Tensorflow deep learning notebook
2. Found NASA MODIS user guide and imagery request website
3. Decided to try Azure for deployment