---
title: "Toy analyses"
teaching: 120
exercises: 5
---

:::::::::::::::::::::::::::::::::::::: questions 

- How can we use momentum and energy to calculate the mass of a particle?
- How do we use this to discover particles too short-lived to travel through our detector?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Understand the basics of how we use 4-vectors in our analyses

::::::::::::::::::::::::::::::::::::::::::::::::

## Background

Most experimental particle physicsts these days use the [python programming language](https://www.python.org/)
in their analyses. Python is used in many fields and many colleges use it as their introductory programning
language.

This section assumes you have some familiarity with python and will show you how to perform some very simple analyses
to discover new particles. We will be making use of open data from the CMS experiment that has been 
reformatted into an even simpler form that you will use in the bulk of the workshop. This will allow you to 
focus on the physics concepts and not let the details of more sophisticated programming approaches get in the way.

*This section is not required but for folks who are brand new to particle physics and experimental analyses, 
it might be a good way to prepare yourself for the more challenging tasks ahead.*


## Particle Physics Playground

The [Particle Physics Playground](https://sites.google.com/siena.edu/particle-physics-playground/home?authuser=0) (PPP)
is a website
maintained by one of our CMS collaborators, [Matt Bellis at Siena College](https://www.siena.edu/faculty-and-staff/person/matthew-bellis/) that provides simplified particle physics data for use in education and training. 

The website provides tutorials and exercises in python, hosted with the [Google Colab](https://colab.research.google.com/) programming
environment. Colab hosts [Jupyter notebooks](https://jupyter.org/) in Google's cloud so that you can run your 
python code from any computer, simply by logging into a Google account. You can test out [Colab here](https://colab.research.google.com/) 
though you will need a Google account. [This is a good tutorial](https://www.tutorialspoint.com/google_colab/google_colab_introduction.htm) on working with Colab and saving files to your account on Google Drive.

*On the Particle Physics Playground, there are a number of Colab notebooks that you can open and run. However, if you want to 
save your edits, you will need to make a copy of your work and save it to your drive. Instructions for how to do this 
are in each notebook*

Let's walk through a series of activities that explain how to work with these data, how to make simpler calculations, 
and how to do a more complicated analysis to discover new particles.

## Working with Colab and the data formats

Go to [this PPP page](https://sites.google.com/siena.edu/particle-physics-playground/documentation-and-help?authuser=0)
and watch the videos

- "Using Colab for the first time"
- "Importing necessary tools into Colab"
- "The data format and how to interface with the data"


## CMS and the data format

Try this [Colab activity](https://drive.google.com/file/d/1bnWOGp5QFbXazHG0JEoBwvFKaPNwuuw_/view?usp=sharing) to learn 
about how to import the data and how it is structured. 

## Lifetimes of particles

Some particles live for very short periods of time before decaying to other particles. In fact, the original
particle may live for such a short period of time that it decays before ever interacting with any of our detectors.

It turns out that only a handful of particle live long enough to actually be detected directly in CMS. Run
through [this activity](https://drive.google.com/file/d/1FXjjfn3FN9AeW_0g1qxWuyGcVvbL48a2/view?usp=sharing) you 
are asked to look up the lifetimes of particles and try to figure out which particles can be detected directly 
in CMS.


## 4-vectors and calculating masses

Particle physicists are always making histograms. *A lot* of histograms. :)  

In [this activity](https://drive.google.com/file/d/1dKh1axZSlNTBHDpyMF4GZPofSIdDeqR1/view?usp=sharing)
you are asked to calculate and make a histogram of the masses of many muons. Hopefully you get a very tight cluster
around 0.105 GeV/c^2. 


## Discovering new particles

For particles that do not live long enough to pass through our detectors, we must infer their existence
by *reconstructing* them from their decay products. We measure their energy and momentum separately and 
use [4-momentum](https://en.wikipedia.org/wiki/Four-momentum) arithmetic to calculate the energy, momentum, 
and mass of the parent particle. 

Go through [this activity](https://drive.google.com/file/d/1HpKTTnQ0i7tEIm1rrMSvnW6uLOjjuApu/view?usp=sharing) to
"discover" new particles by looking for bumps in your histogram plots. 



::::::::::::::::::::::::::::::::::::: keypoints 

- Special relativity provides a mechanism for determining the mass of particles
- We can use the decay products to infer the existence of particle with extremely short lifetimes

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
