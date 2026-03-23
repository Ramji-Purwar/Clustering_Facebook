# Facebook Graph Clustering

A project for analyzing and clustering Facebook social network data using graph-based clustering techniques.

## Overview

This project analyzes the **Facebook Large Page-Page Network**, a webgraph of verified Facebook sites collected through the Facebook Graph API in November 2017. The network consists of official Facebook pages from 4 categories: politicians, governmental organizations, television shows, and companies. 

Nodes represent official Facebook pages while edges represent mutual likes between sites. Node features are extracted from site descriptions created by page owners. The primary task is to identify and analyze the densest clusters in the graph to determine if they form closely knit communities.

## Dataset Characteristics

| Property | Value |
|----------|-------|
| Nodes | 22,470 |
| Edges | 171,002 |
| Density | 0.001 |
| Transitivity | 0.232 |

**Dataset Properties:**
- **Directed**: No
- **Node Features**: Yes
- **Edge Features**: No
- **Node Labels**: Yes (4 categories: politicians, governmental organizations, television shows, companies)
- **Temporal**: No

## Primary Task

**Find the top 5 densest clusters in the graph and observe if they are closely knit communities.**


