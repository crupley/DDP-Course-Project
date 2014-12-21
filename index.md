---
title       : Sine Wave Generator
subtitle    : Developing Data Products - Coursera
author      : Chris Rupley
job         : 
framework   : io2012   # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Description

* The Sine Wave Generator is a simple web application created in R using Shiny.
* Its purpose is to plot a sine wave using input parameters from the user.
* The user can control 3 input parameters: amplitude, frequency, and phase of the sine wave.
* These parameters can be easily set using the slider bars in the page sidebar.

---

## Usage

The sine function has the general form:
$$A\sin(2\pi f + \theta)$$
Where:
* $A$ is the amplitude of the sine wave
* $f$ if the frequency
* $\theta$ is the phase

Using the three slider bars in the left sidebar, the user can adjust these parameters and the resulting sine wave will be automatically plotted. The amplitude can be varied from 0 to 10, the frequency from 1 to 10, and the phase from 0 to 360 degrees.

---

## Example

The application defaults to $A = 1, f = 1, \theta = 0$ which yields the following plot:

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-11.png) ![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-12.png) 

---

## Example, page 2

If we change the inputs to $A = 5, f = 3, \theta = 90$, the plot will update after each change and eventually yeild the following plot:

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-21.png) ![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-22.png) 
