# Beliefs about the development of mental life

## Abstract

Caregiving relationships with infants and children are among the most common and most complex human social interactions. Adults’ perceptions of children’s mental capacities have important consequences for the well-being of children in their care—particularly in the first few years of life, when children’s communication skills are limited and caregivers must infer children’s rapidly developing thoughts, feelings, and needs. In a series of studies, we assessed how US adults conceptualize the development of the human mind over the first five years of life. Exploratory factor analysis identified four core capacities that anchored participants’ representations of the developing human mind: _bodily sensation_ (e.g., hunger, pain), _negative affect_ (e.g., distress, frustration), _social connection_ (e.g., love, learning from others), and _cognition and control_ (e.g., planning, self-control). Participants believed that these capacities were present to different degrees at birth, followed different developmental trajectories, and were driven by different developmental mechanisms, such as biological "preprogramming," physical maturation, passive observation, and social learning. The current studies shed light on this fascinating and understudied aspect of "mind perception" among US adults, in turn highlighting possibilities for theory-based interventions to encourage developmentally appropriate parenting behaviors.

## Guide to repo

This repo includes all analyses and fully reproducible manuscript files for the paper and supplemental materials.

### Data

Datasets are available [here](https://github.com/kgweisman/baby_mental_life_ms/tree/master/data/deidentified). Scripts for cleaning and anonymization can be found [here](https://github.com/kgweisman/baby_mental_life_ms/tree/master/code).

### Analysis

Analysis scripts are embedded in the fully reproducible manuscripts for the supplemental materials ([here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/supplement/supplement-main.Rmd)) and the main text of the paper ([here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/paper/paper.Rmd)).

### Paper

The paper is available as a PDF [here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/paper/paper.pdf), and the supplemental materials [here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/supplement/supplement-main.pdf).

### Figures

All figures related to this project are available [here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/outputs/). The key plots presented in the main text of the paper are displayed below.

#### Figure 1

![Figure 1](https://github.com/kgweisman/baby_mental_life_ms/blob/master/outputs/fig01.jpg?raw=TRUE)

_**Figure 1**: Factor loadings from an exploratory factor analysis of participants’ capacity attributions to newborns, 9-month-old infants, and 5-year-old children in Study 1._

#### Figure 2

![Figure 2](https://github.com/kgweisman/baby_mental_life_ms/blob/master/outputs/fig02.jpg?raw=TRUE)

_**Figure 2**: Perceived developmental trajectories for four domains of mental life among US adults (Studies 2-3). Lighter lines represent individual participants’ responses, black points correspond to mean responses across the sample, error bars are bootstrapped 95% confidence intervals, and thick red lines are predictions from our multilevel generalized additive models. In Study 2 (Panel A), participants assessed 5 capacities within each domain, and assessed all capacities for a given target age before moving on to the next target age. In Study 3 (Panel B), participants assessed 2 capacities within each domain, and assessed a single capacity for all target ages before moving on to the next capacity._

#### Figure 3

![Figure 3](https://github.com/kgweisman/baby_mental_life_ms/blob/master/outputs/fig03.jpg?raw=TRUE)

_**Figure 3**: Figure 3: Perceived importance of various mechanisms in the development of four domains of mental life among US adults (Study 3); see main text for the full text of each mechanism. Small, lighter points represent individual participants’ ratings of how important each developmental mechanism is in the development of each capacity within a domain (top row: bodily sensation; second row: negative affect; third row: social connection; bottom row: cognition and control). Larger black and red points correspond to mean importance ratings across the sample, and error bars are bootstrapped 95% confidence intervals. On the right side of each panel are the percentages of participants who selected each developmental mechanism as the ‘most important’ driver of development for that capacity, with modal selections (including items within 10% of the mode) in red._

#### Figure 4

![Figure 4](https://github.com/kgweisman/baby_mental_life_ms/blob/master/outputs/fig04.jpg?raw=TRUE)

_**Figure 4**: Figure 4: Network graph summarizing the importance of each developmental mechanism (along the bottom) for each capacity (along the top) among US adults (Study 3). Capacities are sorted and color-coded by domain (see Figures 2-3); developmental mechanisms are arranged in the fixed order of presentation (roughly, from what we perceived to be the most innate or biological mechanisms of development, to what we perceived to be the most learned or social). See main text for the full text of each mechanism._

## Programming environment

All analyses were conducted in R (version 4.3.3); platform: aarch64-apple-darwin20 (64-bit); running under: macOS Sonoma 14.5.

The analyses were built using the following packages:

- tidyverse (version 2.0.0) 
- psych (version 2.3.3)
- mgcv (version 1.9-1)
- lme4 (version 1.1-35.3)
- parameters (version 0.21.6)
- kableExtra (version 1.4.0)
- cowplot (version 1.1.1)
- langcog (version 0.1.9001; available at https://github.com/langcog/langcog-package)
- knitr (version 1.43)
- rsq (version 2.5)
- ggnewscale (version 0.4.8)
- GGally (version 2.2.1)
- ggrepel (version 0.9.5)
- igraph (version 2.1.2)
- ggraph (version 2.2.1)
