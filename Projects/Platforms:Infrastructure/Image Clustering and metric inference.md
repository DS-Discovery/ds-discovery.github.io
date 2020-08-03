---
layout: page
title: Image Clustering and metric inference
parent: Platforms/Infrastructure
grand_parent: Projects 
nav_order: 3
---


# Image Clustering and metric inference
*Partner: Brent Morann, Creative Commons, Non-Profit*

## Overview
### Project Description
CC Search (https://search.creativecommons.org/) is a media search engine maintained by Creative Commons which currently indexes metadata for around 500 million images.  As with any search engine, one challenge is ranking the results appropriately. We have many images, but relatively few clicks on these images, and some of our images have little metadata associated with them.  We would like to attempt rectifying this problem by the following steps:
1. Cluster the images based on their perceptual qualities.  An example methodology would be to start by taking a perceptual hash of each image, and associate each image with its k nearest neighbors.
1. Attempt to infer useful metadata about an image based on the metadata available for other images around it.  
  >- Metadata that we’d be interested in would be things like tags, or possibly inferred popularity

We’d also be interested in developing a rigorous methodology for 
>- Showing an image from a given image’s cluster (rather than that image) when it would have appeared in search results, and then
>- analyzing the click-through rate on the alternate image to determine whether our clustering is working well, and perhaps start to develop real data (via clicks) about the alternate image.

For datasets, we currently have almost 100 million (and growing) images (resized for a max dimension of 640px) in our catalog, and we have metadata (tags, descriptions, etc.) for most of the ~500 million images we have indexed.  Common Crawl is also (of course) available if we’d like more raw web data to work with.

### Expected Deliverable
The primary deliverable would be a mapping of the images into some appropriate space and a method for determining the ‘cluster’ associated with each image in that space.  This would imply some label identifying the cluster or clusters associated with an image. Secondarily, methods to derive useful metadata about an image based on its cluster would be fantastic.
### What would a successful semester look like to you?
We’d consider the semester a success if we had the clustering sorted out by the end.  The uses for the clustering would be bonus.
### Additional Skills from ideal candidates
Experience with Apache (Py)Spark would be great, since that’s a tool we’re currently using at CC for processing large datasets.

## Data

## Models

## Conclusion


```python

```
