---
title: "Satellite tools"
excerpt: "The satellite tools developed in the QUANTICOL Project"
sitemap: true
layout: single
permalink: /satellite.html
---
{% include toc %}

## Bus Data Visualiser

This is a tool developed to support the automatic derivation of patch-based models from real data (specifically, GPS measurements). The tool is based on an API made publicly available by [Lothian Buses](http://www.mybustracker.co.uk/?page=%20API%20Key) that allows developers to access live bus GPS data. It can be made to collect data, which is then stored in a database so that it can be visualised at any time. In addition, it is also able to visualise live data.

The visualisation tool is implemented as a web application in JavaScript using jQuery and Bootstrap, with a back-end NoSQL database using Node.js and MongoDB. The tool is currently available [here](http://ec2-52-28-155-29.eu-central-1.compute.%20amazonaws.com:3000/#/tool). Documentation for installation procedure on a local machine is available at this [link](http://ec2-52-28-155-29.eu-central-1.compute.amazonaws.com:3000/#/doc).

## FlyFast

This is a tool that offers an efficient on-the-fly algorithm for model checking PCTL formulae including scalable mean field approximation. FlayFast is provided within [jSAM framework](http://j-sam.sourceforge.net/).

## CRNReducer

CRNReducer provides algorithms for the exact reduction of ordinary differential equa- tions (ODEs) arising from chemical reaction networks with mass-action semantics. The [tool](http://sysma.imtlucca.it/crnreducer/) currently supports CRNs given in the “.net” format generated with the well-established tool [BioNetGen](http://bionetgen.org/index.php/Main_Page).

## PALOMA Eclipse plugin

The PALOMA Eclipse plugin provides a fully-featured development environment for modelling with the recently proposed PALOMA process algebra. The plug-in consists of:

An editor for PALOMA models with syntax highlighting functions;
A simulator which supports population-level stochastic simulation of PALOMA models using Gillespie’s algorithm;
Plotting facilities for simulation results;
A generator which can translate a PALOMA model to directly runnable Matlab scripts for moment-closure analysis using ODEs [FHG].
The source code of the plug-in is available [here](https://github.com/cfeng783/paloma). A user manual about how to install and use the plug-in can be found at this [link](http://groups.inf.ed.ac.uk/paloma/usermanual.pdf). Once the plug-in is installed, one can create a PALOMA model, parse it and then do time-series analysis of the model by stochastic simulation and moment-closure approximation. In the following we show the typical workflow supported by the tool.

## Topochecker: a topological model checker

Topochecker is a spatio-temporal model checker based on closure spaces and Kripke frames. Currently it checks a spatial extension of CTL named STLCS (spatio-temporal logic of closure spaces).
The current version of topochecker, given its prototypical nature, is available in source code form at [github](https://github.com/vincenzoml/topochecker), where you can find more information, download the tool and experiment with it.

## jSSTL

jSSTL is a Java tool for the specification and verification of SSTL. This tool, developed in Java, consists of a Java library (jSSTL API) and a front-end, integrated in ECLIPSE.
