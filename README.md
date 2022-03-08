# kooragang

This repository contains code for analysing classified drone imagery from Fish Fry Flat, Kooragang wetlands, NSW. The code could also be used to analyse classified images from other wetlands/ecosystems.

The "class_areas" script calculates total areas for each class in classified images.

The "accuracy" script takes input summary data for producer's and user's accuracy and plots accuracy over time for each class.

The "variable_importance" script takes GINI variable importance summary data, produced during the classification process, and plots the relative importance of different image bands and object features, as well as testing for differences in importance of bands/features.

The "environmental_vars" script tests for changes in the elevation of classes of interest over time, and also plots elevation summaries and trends.

The "patch_metrics" script calculates patch metrics (on a class and landscape scale) to investigate patterns of change in classes of interest. It tests for significance changes in patch metrics and plots these trends.
