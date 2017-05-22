---
title: "Satellite tools"
excerpt: "The satellite tools developed in the QUANTICOL Project"
sitemap: true
layout: single
permalink: /satellite.html
---
{% include toc %}

## Bus Data Visualiser

The QUANTICOL Bus Simulator supports the automatic derivation of patch-based models from real data (specifically, GPS measurements).
+ The tool is based on an API made publicly available by Lothian Buses that allows developers to access live bus GPS data. It can be made to collect data, which is then stored in a database so that it can be visualised at any time. In addition, it is also able to visualise live data.
+ The QUANTICOL Bus Simulator is hosted at the following [link](http://pepa.inf.ed.ac.uk:3000/).

## FlyFast

This is a tool that offers an efficient on-the-fly algorithm for model checking PCTL formulae including scalable mean field approximation. FlayFast is provided within [jSAM framework](https://quanticol.github.io/jSAM/).

## ERODE

ERODE is a software tool for the solution and exact reduction of systems of ordinary differential equations (ODEs).
+ The tool supports two recently introduced, complementary, equivalence relations over ODE variables: forward differential equivalence partitions ODE variables into blocks for which a self-consistent aggregate ODE system can be obtained; each aggregate ODE gives the cumulative dynamics of the sum of the original variables in the respective equivalence class. Backward differential equivalence identifies variables that have identical solutions whenever starting from the same initial conditions.
+ ERODE uses a backend based on the well-known Z3 SMT solver to compute the coarsest equivalence that refines a given initial partition. In the special case of ODEs with polynomial derivatives of degree at most two, covering elementary chemical reaction networks (CRNs) and continuous time Markov chains (CTMCs), it implements a more efficient partition-refinement algorithm.
+ It is available from [http://sysma.imtlucca.it/tools/erode/](http://sysma.imtlucca.it/tools/erode/).



## PALOMA Eclipse plugin

The PALOMA Eclipse plugin provides a fully-featured development environment for modelling with the recently proposed PALOMA process algebra. The plug-in consists of:

+ An editor for PALOMA models with syntax highlighting functions;
+ A simulator which supports population-level stochastic simulation of PALOMA models using Gillespie’s algorithm;
+ Plotting facilities for simulation results;
+ A generator which can translate a PALOMA model to directly runnable Matlab scripts for moment-closure analysis using ODEs [FHG].

The source code of the plug-in is available [here](https://github.com/cfeng783/paloma). A user manual about how to install and use the plug-in can be found at this [link](http://groups.inf.ed.ac.uk/paloma/usermanual.pdf). Once the plug-in is installed, one can create a PALOMA model, parse it and then do time-series analysis of the model by stochastic simulation and moment-closure approximation. In the following we show the typical workflow supported by the tool.

## Topochecker: a topological model checker

Topochecker is a spatio-temporal model checker based on closure spaces and Kripke frames. Currently it checks a spatial extension of CTL named STLCS (spatio-temporal logic of closure spaces).
The current version of topochecker, given its prototypical nature, is available in source code form at [github](https://github.com/vincenzoml/topochecker), where you can find more information, download the tool and experiment with it.

## jSSTL

jSSTL is a Java tool for the specification and verification of SSTL. This tool, developed in Java, consists of a Java library (jSSTL API) and a front-end, integrated in ECLIPSE. The tool is available [here](http://quanticol.sourceforge.net/?page_id=109).
