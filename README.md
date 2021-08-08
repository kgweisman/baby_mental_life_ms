# Beliefs about the development of mental life

### Kara Weisman ([website](http://kgweisman.github.io/)), Lucy S. King ([website](https://www.lucysking.com/)), & Kathryn L. Humphreys ([website](http://www.kathrynhumphreys.com/))

### Abstract

In a series of large-scale studies we assessed how US adults conceptualize the development of the human mind over the first five years of life. Exploratory factor analysis identified four categories of mental capacities that anchored participants’ representations of the developing human mind: _bodily sensations_ (e.g., hunger, pain), _negative affect_ (e.g., distress, frustration), _social connection_ (e.g., love, learning from others), and _cognition and control_ (e.g., planning, self-control). Participants perceived that these four aspects of mental life were present to different degrees at birth, followed different developmental trajectories, and were driven by different developmental mechanisms (such as biological "preprogramming," physical maturation, passive observation, and social learning). These studies reveal the lay theories that govern US adults’ understanding of the development of the human mind, illuminating the cognitive architecture that supports some of the most important social interactions: caregiving relationships with infants and children.

### Guide to repo

This repo includes all analyses and fully reproducible manuscript files for the paper and supplemental materials.

#### Data

Datasets are available [here](https://github.com/kgweisman/baby_mental_life_ms/tree/master/data/deidentified). Scripts for cleaning and anonymization can be found [here](https://github.com/kgweisman/baby_mental_life_ms/tree/master/code).

#### Analysis

Analysis scripts are embedded in the fully reproducible manuscripts for the supplemental materials ([here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/supplement/supplement-main.Rmd)) and the main text of the paper ([here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/paper/paper.Rmd)).

#### Paper

The paper is available as a PDF [here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/paper/paper.pdf), and the supplemental materials [here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/supplement/supplement-main.pdf).

#### Figures

The key plots presented in the main text of the paper are displayed below.

##### Figure 1

![Figure 1](https://github.com/kgweisman/baby_mental_life_ms/blob/master/outputs/fig01.jpg?raw=TRUE)

_**Figure 1**: Factor loadings from an exploratory factor analysis of participants’ capacity attributions to newborns, 9-month-old infants, and 5-year-old children in Study 1._

##### Figure 2

![Figure 2](https://github.com/kgweisman/baby_mental_life_ms/blob/master/outputs/fig02.jpg?raw=TRUE)

_**Figure 2**: Perceived developmental trajectories for four domains of mental life (Studies 2-3). Lighter lines represent individual participants’ responses, black points correspond to mean responses across the sample, error bars are bootstrapped 95% confidence intervals, and thick red lines are predictions from our generalized additive models (beta regressions). In Study 2 (Panel A), participants assessed 5 capacities within each domain, and assessed all capacities for a given target age before moving on to the next target age. In Study 3 (Panel B), participants assessed 2 capacities within each domain, and assessed a single capacity for all target ages before moving on to the next capacity._

##### Figure 3

![Figure 3](https://github.com/kgweisman/baby_mental_life_ms/blob/master/outputs/fig03.jpg?raw=TRUE)

_**Figure 3**: Perceived importance of various mechanisms in the development of four domains of mental life (Study 3); see main text for the full text of each mechanism. Panel A shows ratings for each developmental mechanism and both of the capacities within each domain; Panel B shows mean ratings for extrinsic vs. intrinsic mechanisms for each domain of capacities; and Panel C shows the percentage of trials on which participants selected extrinsic vs. intrinsic mechanisms as the 'most important' driver of development. Lighter points and lines represent individual participants’ responses, black points correspond to mean scores across the sample, and error bars are bootstrapped 95% confidence intervals. The dotted red line at the midpoint of the response scale in Panels A and B is intended to aid visual comparison across domains._

### Programming environment

All analyses were conducted in R (version 4.1.0); platform: aarch64-apple-darwin20 (64-bit); running under: macOS Big Sur 11.4.

The analyses were built using the following packages:

- tidyverse (version 1.3.1) 
- psych (version 2.1.6)
- mgcv (version 1.8-36)
- lme4 (version 1.1-27.1)
- ggdendro (version 0.1.22)
- dendextend (version 1.15.1)
- parameters (version 0.14.0)
- kableExtra (version 1.3.4)
- cowplot (version 1.1.1)
- langcog (version 0.1.9001; available at https://github.com/langcog/langcog-package)
- knitr (version 1.33)
