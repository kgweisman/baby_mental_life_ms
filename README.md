# Beliefs about the development of mental life

[authors removed to preserve anonymity]

**Abstract**: In a series of large-scale studies we assessed how US adults conceptualize the development of the human mind over the first five years of life. Exploratory factor analysis identified four categories of mental capacities that anchored participants’ representations of the developing human mind: _bodily sensations_, _negative affect_, _social connection_, and _cognition and control_. Participants perceived that these four aspects of mental life were present to different degrees at birth, followed different developmental trajectories, and were driven by different developmental mechanisms (e.g., biological "preprogramming," physical maturation, passive observation, social learning). These studies reveal the lay theories that govern US adults’ understanding of the development of the human mind, illuminating the cognitive architecture that supports some of the most important social interactions: caregiving relationships with infants and children.

This repo includes all analyses and fully reproducible manuscript files for the paper and supplemental materials.

**Datasets** are available [here](https://github.com/kgweisman/baby_mental_life_ms/tree/master/data/deidentified). Scripts for cleaning and anonymization can be found [here](https://github.com/kgweisman/baby_mental_life_ms/tree/master/code).

**Analysis scripts** are embedded in the fully reproducible manuscripts for the supplemental materials ([here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/supplement/supplement-main.Rmd)) and the main text of the paper ([here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/paper/paper.Rmd)).

The **paper** is available as a PDF [here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/paper/paper.pdf), and the **supplemental materials** [here](https://github.com/kgweisman/baby_mental_life_ms/blob/master/supplement/supplement-main.pdf).

**Programming environment**: All analyses were conducted in R (version 4.1.0); platform: aarch64-apple-darwin20 (64-bit); running under: macOS Big Sur 11.4.

The analyses were built using the following packages:

- tidyverse (version XX) 
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
