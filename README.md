# Gatherplot - A Non-Overlapping Scatterplot

An interactive article in the [Journal of Visualization and Interaction (JoVI)](https://journalovi.org/).

## Abstract

#### Introduction
Scatterplots are a common tool for exploring multidimensional datasets, especially in the form of scatterplot matrices (SPLOMs).
However, scatterplots suffer from overplotting when categorical variables are mapped to one or two axes, or the same continuous variable is used for both axes.
Previous methods such as histograms or violin plots use aggregation, which makes brushing and linking difficult.

#### Conclusion

We propose gatherplots, an extension of scatterplots to manage the overplotting problem.
Gatherplots are a form of *unit visualization*, which avoid aggregation and maintain the identity of individual objects to ease visual perception.
In gatherplots, every visual mark that maps to the same position coalesces to form a packed entity, thereby making it easier to see the overview of data groupings.
The size and aspect ratio of marks can also be changed dynamically to make it easier to compare the composition of different groups.
In the case of a categorical variable vs. a categorical variable, we propose a heuristic to decide bin sizes for optimal space usage.
Results from a crowdsourced user study show that gatherplots enable people to assess data distribution more quickly and more correctly than when using jittered scatterplots.

#### Materials

Source code for Gatherplots can be found at [https://github.com/intuinno/gatherplot](https://github.com/intuinno/gatherplot).
Research materials associated with the crowdsourced user study can be found on OSF at [https://osf.io/bk9cx/](https://osf.io/bk9cx/).

#### Data Collection

We conducted a crowdsourced user study on [Amazon Mechanical Turk](https://www.mturk.com/) involving participants drawn from the general population.
We collected completion time, accuracy, and confidence for five different retrieval, ranking, and comparison tasks under four conditions: scatterplots with jittering, gatherplots with absolute mode, gatherplots with normalized mode, and gatherplots with a toggle to switch between absolute and normalized mode.

#### Data Analysis

Data collected from the crowdsourced survey were analyzed with respect to the accuracy (correct or incorrect), time spent, and confidence of estimation.
Based on our hypotheses, we analyzed the different modes of layout for each type of question: retrieve value, absolute value task, and relative value task.

#### Analysis Results

Gatherplots outperform jittering for accuracy as well as for the subjective confidence measure.

#### Implementation

We implemented a web-based demonstration of Gatherplots using [D3](https://d3js.org/) and [Firebase](https://firebase.google.com/), as well as using [Observable JS](https://observablehq.com/) in this article.

#### Demonstration

Beyond the embedded demonstration in this article, you can also find a live demo of Gatherplots at [https://gatherplot.firebaseapp.com/](https://gatherplot.firebaseapp.com/).

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

```
Authors: @nickelm
OC: @mjskay
AE: @codementum
R1: @joviewer-xyz
R2: @facet-fan
R3: @jov-anonymous-reviewer-AAAA (later @jov-anonymous-reviewer-AAAA-proxy)
```
