# CCAL-Executable in Maude for paper : A Process Calculus Integrating Data Protection by Design and Default 
Introduction

This repository contains Maude formalization for a submitted work A Process Calculus Integrating Data Protection by Design and Default .

Prerequisites

To run and test the code, the rewriting tool [[http://maude.cs.illinois.edu/][Maude version 3.1]](https://maude.cs.illinois.edu/w/index.php/Maude_download_and_installation) is needed. It's downloadable free of charge from the University of Illinois. See the documentation there for installation instructions and further information.

CCAL's formalization in Maude

CACL's data, syntax and  operational semnatics are specified in the file Pical.maude. Hygienic and non-hygienic programs are specified in the files ExampleHygenic and Example-nonHygenic.maude

Instructions

Download Maude 3.1 and the files listed on /maude in the same directory. After installing Maude, test the properties for our hygienic program, use the following commands in your terminal:

sudo ./maude-Yices2.darwin64 <br>
load Pical.maude <br>
load Hygenicexample.maude <br>
load nonHygenicexample.maude <br>
