---
layout: default
title: Erroneous High Occupancy Vehicle (HOV) Degradation
parent: Engineering
grand_parent: Projects 
nav_order: 2
---

## Erroneous High Occupancy Vehicle (HOV) Degradation
*Partner: Yashar Farid,California Partners for Advanced Transportation Technology (PATH), Government & Academic*

## Overview
### Project Description
In a recent review of Performance Measurement System (PeMS) data quality for the Connected Corridors project along the I-210 corridor, it was discovered that almost 10% of HOV loops along 30-miles of freeway were actually located in the mainline. Since mainline lanes are impacted more severely by congestion during peak periods than HOV lanes, they exhibit lower speeds during these times of day. As a result, it is possible that this erroneous configuration contributes to wrongful HOV lane degradation in performance reports.

The Connected Corridors team at PATH is working on a project for Caltrans to explore the application of machine learning techniques to improve the accuracy of measurements and therefore directly improve the quality of management decisions. The main goal is to develop automated means to identify configuration errors of HOV lanes.

The project includes wide range of data science and machine learning tools and techniques. Data pipeline needs to collect data, clean, preprocess and add required features.  Ground truth data from the I-210 pilot project will be used to develop classification models for identifying the misconfigured labels. In addition, unsupervised techniques will be applied on District 7 data to detect anomalies.
### Expected Deliverable
The students will work on creating the pipeline from downloading and processing the data to implementing supervised and unsupervised models to identify misconfigured detectors. Finally, a tool (HTML) twill be developed to visualize the results.
### What would a successful semester look like to you?
At the end, we will have a running pipeline on Amazon AWS that automatically collects data, preprocess it, runs the models, dumps the results in an s3 bucket, and finally the HTML tool shows the results.

## Data

## Models

## Conclusion


```python

```
