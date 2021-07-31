# Beliefs about the development of mental life

Authors: Kara Weisman, Lucy S. King, & Kathryn L. Humphreys

Repository related to psychological studies exploring methods for capturing intuitive theories as Bayesian networks using structure learning techniques.

Manuscript in preparation, title may change. Nothing here is final. please contact if you have any questions about this project or code. For related work, see [this repo](https://github.com/kgweisman/baby_mental_life).

## Abstract

In a series of large-scale studies we assessed how US adults conceptualize the development of the human mind over the first five years of life. Exploratory factor analysis identified four categories of mental capacities that anchored participants’ representations of the developing human mind: _bodily sensations_, _negative affect_, _social connection_, and _cognition and control_. Participants perceived that these four aspects of mental life were present to different degrees at birth, followed different developmental trajectories, and were driven by different developmental mechanisms (e.g., biological "preprogramming," physical maturation, passive observation, social learning). These studies reveal the lay theories that govern US adults’ understanding of the development of the human mind, illuminating the cognitive architecture that supports some of the most important social interactions: caregiving relationships with infants and children.

## Repository Overview

* `paper/`: Rmarkdown and supporting files for creation of the manuscript. Must run supplemental materials notebook first.
* `supplement/`: Rmarkdown and supporting files for creation of the supplemental materials.
* `data/`: Data for all studies reported in paper.
* `code/`: Code scripts on which all Rmarkdown notebooks depend.

## Reproducibility notes

_Thanks to [Derek Powell](https://github.com/derekpowell) for providing a model of a fully reproducible manuscript, which we have closely followed here._

To reproduce the manuscript and all analyses, follow the following steps after cloning this repository.

1. Create a `local/` folder in the repository (at the terminal: `mkdir local`)
2. Install required packages by running `install-packages.R` to make sure you have all packages needed.
3. Open and knit `supplement/supplement-main.Rmd` to generate supplement PDF and save files needed for reproduction of manuscript.
4. Open and knit `paper/paper-main.Rmd` to generate manuscript PDF.

