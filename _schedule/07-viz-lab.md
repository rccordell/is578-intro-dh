---
title: "Lab: Visualizing Networks"
permalink: /schedule/07-viz-lab/
toc: true
class_date: 2024-10-10
---

## Lab Topic

#### [Collaborative Lab Notes Doc](https://docs.google.com/document/d/15-vDrETg9c1xSr440KP0f1zBvEgvygwCS01D4PjnPLU/edit?usp=sharing)

### Instructions

Hopefully, you've already downloaded [Gephi](https://gephi.org), but if not you will need it for today's workshop.

We will be using [Melanie Walsh's sample network datasets](https://github.com/melaniewalsh/sample-social-network-datasets/tree/master) today as well as data from the [_Mapping the Republic of Letters_](http://republicofletters.stanford.edu) project. I've gathered the files here for you to download (you will click the `Download Raw File` button, just under `History`). If you're on a mac, double-click the zip to extract the files; if you're on Windows you'll need to right click and select `Extract All`.

+ [Walsh sample network data](https://github.com/rccordell/is578-intro-dh/blob/gh-pages/public_course_data/network-data/sample-social-network-datasets-master.zip)
+ [Mapping the Republic of Letters network data](https://github.com/rccordell/is578-intro-dh/blob/gh-pages/public_course_data/network-data/mapping-republic-letters.zip)

---

There are many kinds of visualizations in digital humanities work—graphs, charts, maps, trees, timelines, &c.—but today we'll focus on one: the network graph. Networks are used to analyze and visualize relationships. And though we often think of networks primary _as_ visualizations, this lab will seek to demonstrate how those visualizations are only one aspect—and often not the most important aspect—of a network analysis.

Building on our discussion of Benjamin Schmidt's argument in ["Do Digital Humanists Need to Understand Algorithms?"](https://dhdebates.gc.cuny.edu/read/untitled/section/557c453b-4abb-48ce-8c38-a77e24d3f0bd#:~:text=Put%20simply%3A%20digital%20humanists%20do,algorithms%20attempt%20to%20bring%20about.), we will discuss a number of key metrics from the field of social network analysis—e.g. degree, centrality, betweenness—with an eye toward understanding how they are computed from network data. 

Let's start by looking together [at this network graph of _Star Wars_ characters](http://evelinag.com/data/2016/social-network-force-awakens/interactions.html). Note that if you hover over a node, the character name will appear. The creator has written about how this graph was created and what it represents, but I want you to first write down some hypotheses. What do you think is being measured about these characters here, and how is that measurement being determined?

#### Lab Task: Build & analyze your own network

Using either one of the datasets from Melanie Walsh that we did not discuss in class or assembling your own edges and nodes:

1. Import or create an edges and nodes table
2. Run the major network metrics: degree, centrality, betweenness, modularity. You can experiment with others.
3. Experiment with the layout and visualization of your network based on these metrics. Be sure to look at the numbers in addition to the visualization itself.
4. Draft a lab report, following the general guidelines for lab reports, that reflects on these qualities. What have you learned (or not) about your network using these methods? What would you need to better understand to take full advantage of these methods?

### Resources

+ Scott Weingart, [Networks Demystified series](https://www.scottbot.net/HIAL/index.html@tag=networks-demystified&paged=2.html) (or the first two parts at the [_Journal of Digital Humanities_](https://journalofdigitalhumanities.org/1-1/demystifying-networks-by-scott-weingart/))
+ Martin Grandjean Tutorial to Gephi (2015), [external link](https://www.martingrandjean.ch/gephi-introduction/)
+ Miriam Posner's List of Data Visualization Tools (2023), [external link](http://miriamposner.com/classes/dh201w23/tutorials-guides/data-visualization/dataviz-tools/)
+ _Programming Historian_'s [network analysis lessons](https://programminghistorian.org/en/lessons/?topic=network-analysis) and [mapping lessons](https://programminghistorian.org/en/lessons/?topic=mapping)
+ [Six Degrees of Francis Bacon](http://sixdegreesoffrancisbacon.com/)
+ [Stanford Large Network Dataset Collectio](https://snap.stanford.edu/data/)

