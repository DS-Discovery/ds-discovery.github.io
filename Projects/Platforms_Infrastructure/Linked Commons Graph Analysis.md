---
layout: page
title: Linked Commons Graph Analysis
parent: Platforms/Infrastructure
grand_parent: Projects 
nav_order: 5
---


# Linked Commons Graph Analysis
*Partner:Brent Moran, Creative Commons, Non-Profit*

## Overview
### Project Description
Creative Commons has collected graph data linking different web properties that use Creative Commons licenses.  Nodes are domains (rather than, e.g., individual pages).  For each node, we record the number of CC Licenses and their types found at that domain.  The edges (as one might imagine) are  links between two domains, and are weighted by how many links there are between the two domains.  We currently have a graph with about 250,000 nodes.
>- How can we quantify the ‘influence’ of a node within the ‘Commons’, i.e., the set of domains hosting CC Licensed content?  It would be interesting to integrate a standard metric (PageRank) with some metric that takes into account the number of CC Licensed works hosted at a domain.
>- How can we define and find communities within the Commons using this graph?  (perhaps k-cores, but those are usually defined on undirected graphs).
>- Are there choke points or ‘narrow’ spots in the graph? (Think minimal cuts, or maybe minimal tree-decompositions)

We’d also be open to other ideas for analyzing the graph as appropriate.  In particular, it would be interesting to explore metrics that either Creative Commons, or domains hosting CC Licensed content, could use when seeking funding from donors."
### Expected Deliverable
An Apache (Py)Spark job or other (preferably Python-centric) script that calculates the metrics would be great.  CC also has an (in development) web app that displays the graph (or a subgraph chosen by the user) and it would be great if any of these metrics could be incorporated into that UI. Because Creative Commons isn’t using Azure for infrastructure, we’d need to make sure that any code was designed so that it could be run (or modified to run) on other cloud platforms.
### What would a successful semester look like to you?
The ‘questions of interest’ above are in descending order of preference. It would be fantastic if we had the first one answered convincingly, and if we had an implementation to calculate the metric quantifying the influence of a node in the Commons whenever we collect new graph data (we already have the data collection step implemented).
### Additional Skills from ideal candidates
Experience with Apache (Py)Spark would be great, since that’s a tool we’re currently using at CC for processing large datasets. Calculating PageRank on a graph with 250,000 nodes will likely require working with some system for handling relatively large matrices.

## Data

## Models

## Conclusion


```python

```
