# URL: https://github.com/4dn-dcic/2017-annual-meeting-higlass-hipiler-tutorial


# 4DN Annual Meeting 2017: 3D Genome Data Visualization Tutorial

## Organizers & Presenters

* [Peter Kerpedjiev](http://emptypipes.org/about), Postdoctoral Research Fellow, Harvard Medical School
* [Fritz Lekschas](http://lekschas.de), PhD student, Harvard University
* [Nils Gehlenborg](http://gehlenborglab.org), Assistant Professor, Harvard Medical School

## Files and Links:

* HiGlass Tutorial - [https://4dn-dcic.github.io/2017-annual-meeting-higlass-hipiler-tutorial/](https://4dn-dcic.github.io/2017-annual-meeting-higlass-hipiler-tutorial/)
* HiPiler Tutorial - [hipiler-presentation.pdf](https://github.com/4dn-dcic/2017-annual-meeting-higlass-hipiler-tutorial/blob/master/hipiler-presentation.pdf?raw=true) | [hipiler-presentation.key](https://github.com/4dn-dcic/2017-annual-meeting-higlass-hipiler-tutorial/blob/master/hipiler-presentation.key?raw=true)

## Feedback

We've created a [very short questionnaire to help us improve our
tools](https://goo.gl/forms/jCllHdoSvaK8SIUv2). If you have a moment, we would
love to hear about what you're working on and how we can help you
explore your data.


## Motivation

Due in large part to the explanatory power of chromosome organization in gene
regulation, its association with disease and disorder as well as the unanswered
questions regarding the mechanisms behind its maintenance and function, the 3D
structure and function of the genome are becoming increasingly target of
scientific scrutiny. With efforts such as the 4D Nucleome Project and ENCODE 4
already beginning to generate large amounts of data, the ability to analyze and
visualize it will be a valuable asset to any computational biologist tasked
with interpretation of experimental results.


## Objectives

The objectives of this tutorial are:

* To introduce the capabilities of HiGlass and HiPiler for visual exploration for large genomic data sets
* To provide a hands on experience in setting up the infrastructure and loading data for visualization.


## Goal

After the tutorial participants should know about the functionality of HiGlass and HiPiler to visually explore sequencing-based 3D genome data as well as how to get started using the tools on their own.


## Intended audience and level

The subject matter and practical exercises presented in this tutorial will be accessible to a broad audience. Prior experience with next generation sequencing and the data it produces will be helpful for understanding the underlying processes.

The material will be most useful to computational biologists and biologists working on genomics-related topics.


## Requirements:

* Install Docker
  * https://www.docker.com/community-edition
* Install Miniconda
  * https://conda.io/miniconda.html  
* Windows users
  * Putty (for ssh)
  * https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
* Python with Pandas
  
  
## Agenda

**4:40 - 4:45 - Introduction and Overview**

* Who are we and what we'll cover? [5 minutes]

**4:45 - 5:15 Hi-C Visualization Hi-C Data with HiGlass [Peter]**

* 25 minutes: 
  * Overview of common operations such as adding tracks, removing tracks, adding views, removing view, linking views by zoom and location
    * Horizontal heatmaps and flipping them
    * Value scaling locking
    * Export link, SVG and JSON
  * Practical: 
    * Create an interactive version of a figure
* 10 minutes: Installing HiGlass
  * Overview of the HiGlass architecture and description of the infrastructure used to run it
  * Practical: 
    * Create a local HiGlass instance
    * Convert a contact map to multi-resolution format and import it
    * Convert a bigWig file to hitile format and import it
    * Open both files in the client and navigate to an interesting location

**5:15 - 5:35 Feature-centric Visualization: An Intro to HiPiler [Fritz]**

* What can you do with HiPiler [12min]
* How to load features from a BEDPE file into HiPiler [5min]
* Questions [3min]

**5:35 - 5:40 Feedback from the audience**

* What would you like to see added?
* What data would you like to bring in?
* Why are you here?
* Is there something you work on that we can make easier?
* Come talk to us!

## Instructor Bios


### Peter Kerpedjiev

Peter is a postdoctoral researcher working on creating tools (such as HiGlass) for visualizing large genomic data sets. Web site: http://emptypipes.org/about

### Fritz Lekschas

Fritz is a PhD student working on biomedical information visualization with focus on large multiscale genomic data sets. http://lekschas.de

### Nils Gehlenborg

Nils is an Assistant Professor in the Department of Biomedical Informatics at Harvard Medical School. His research group is developing tools to visualize 3D genome conformation data as well as heterogeneous data from large-scale cancer genomics studies. http://gehlenborglab.org 

**Papers:**

* Kerpedjiev, Peter, et al. "HiGlass: Web-based Visual Comparison And Exploration Of Genome Interaction Maps" bioRxiv. doi:[10.1101/121889](https://doi.org/10.1101/121889)
* Lekschas, Fritz et al. "HiPiler: Visual Exploration Of Large Genome Interaction Matrices With Interactive Small Multiples" IEEE Transactions on Visualization and Computer Graphics, InfoVis 2017. [doi:10.1101/123588](https://vcg.seas.harvard.edu/publications/hipiler-visual-exploration-of-large-genome-interaction-matrices-with-interactive-small-multiples)
