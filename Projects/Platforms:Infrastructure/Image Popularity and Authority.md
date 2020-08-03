---
layout: page
title: Image Popularity and Authority
parent: Platforms/Infrastructure
grand_parent: Projects 
nav_order: 4
---


## Image Popularity and Authority
*Partner:Brent Morann, Creative Commons, Non-Profit*

## Overview
### Project Description
CC Search (https://search.creativecommons.org/) is a media search engine maintained by Creative Commons which currently indexes metadata for around 500 million images.  As with any search engine, one challenge is ranking the results appropriately.  
>- The ‘authority’ of an image is defined (for us) by the probability that someone would end up looking at a particular image, given that they’re puttering around the internet looking for images in general.  For general webpages, the typical example of such a metric is PageRank.
>- The ‘popularity’ is simply how many people have viewed/liked/commented on a given image (or some balance of these).

These metrics are likely correlated with each other, but distinct.  For example, a particularly shocking image may get passed around a lot, and therefore viewed, but won’t be linked very often from mainstream sites. Generally, we gather metadata from APIs provided by image hosts, many of which are cultural institutions such as museums.  For two of our providers, we have metrics available to help us understand which images should be ranked higher, based on their popularity or authority.  Because it’s probable that popularity metrics would not be comparable between different providers, we’ve also developed a standardization procedure to map raw metrics into the same (or at least similar) distributions.  For many providers, however, we have no metric available from their API that describes (at least directly) the popularity or authority of a given image.  We’re interested in finding ways to measure these metrics for such images.  

Questions we’d love to answer would be:

1. Is it possible to develop an authority metric that can be derived from the image data itself?  What about EXIF data?  For inspiration, one could search for ‘ImageRank’ or ‘VisualRank’ and look at Google Papers and patents related to this question.
1. What about inheriting popularity or authority from the site or domain that hosts the image?
1. Failing (1) and (2), perhaps we could try to gather more data from Common Crawl and process it to try to determine an authority metric for the pages containing a given image.

For datasets, we currently have almost 100 million (and growing) images (resized for a max dimension of 640px) in our catalog, and we have metadata (tags, descriptions, etc.) for most of the ~500 million images we have indexed.  Common Crawl is also (of course) available if we’d like more raw web data to work with.

### Expected Deliverable
We would like numbers between 0 and 1 describing popularity, authority, and/or some similar concept for each image in our Catalog, and an implemented process to (re)calculate those numbers.
### What would a successful semester look like to you?
If we get that deliverable, we'd be extremely pleased. However, we consider this to be an open-ended research question, and making any significant progress towards understanding how to derive useful metrics from image data itself would be amazing."
### Additional Skills from ideal candidates
We’re using Apache (Py)Spark quite a bit at the moment for dealing with large data sets, so familiarity with that environment would likely be helpful.

## Data

## Models

## Conclusion


```python

```
