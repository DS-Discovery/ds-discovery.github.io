---
layout: default
title: Modeling Access Pattern of Large Scientific Data Repository with Machine Learning
parent: Engineering
grand_parent: Projects 
nav_order: 4
---

# Modeling Access Pattern of Large Scientific Data Repository with Machine Learning
*Partner: John Wu, Lawrence Berkeley National Laboratory, Academic*

## Overview
### Project Description
Large amounts of data is archived on the tape archive (HPSS), especially for those experiments that produce large volumes of data every year. dCache system is a storage management system that has an HPSS connectivity, and transfers data from HPSS to designated storage disks when the users request. The issue is that tape mounting on HPSS to retrieve the file is an overhead for every single tape mounting, besides seeking time for the requested file on the tape and reading time for the file. From the system point of view, reading multiple files out of the same tape can increase the lifetime of the tape, and from the user point of view, data access latency could be reduced, and overall performance can increase. So, if we can predict the files to be requested by the user access patterns, we can reduce the overhead from the multiple tape mounting, for example by reading multiple files from the same tape once it’s mounted, or by prestaging the files before they are requested.  
The main research goal is to develop methods and tools for data access pattern analysis and prediction. It includes following tasks:    
>* Pre-processing of the dCache HPSS logs is completed (5/2020). 
>* Data exploration to study data for access patterns (e.g. clustering)
>* Development of a machine learning method for to predict the access pattern (with error analysis)
>* Development of model update and synchronization method for more data

### Expected Deliverable
Report on the common patterns discovered.

### What would a successful semester look like to you?
Report on the common patterns discovered.

## Data

## Models

## Conclusion


```python

```
