---
title: 'SEED: Software for the Extraction of Equations from Data'
tags:
  - Python
  - graphical user interface
  - dynamical systems
  - model discovery
  - system identification
authors:
  - name: Kyle Kean
    affiliation: 1
  - name: Rui Carvalho
    orcid: 0000-0002-3279-4218
    affiliation: 1
affiliations:
  - name: Department of Engineering, Durham University
    index: 1
date: 21 February 2021
bibliography: paper.bib
---

# Summary

Scientific discovery in the present day is led by machine learning and data-driven methods due to an abundance of
measurement options for collecting data from a system. However, while a huge amount of data revelant to a 
system's behaviour can be collected, the key governing equations are sparse in the space of basis functions. `SEED` 
is a simple and intuitive Graphical User Interface (GUI) for the Python package PySINDy [@deSilva2020] which allows for
the extraction of governing differential equations from data. The GUI provides the cutting-edge data-driven methods to 
researchers in a wide variety fields without any need for prior programming knowledge.

# Statement of Need

Research in system identification in the Modern Era is primarily led by data-driven methods, such as Dynamic Mode 
Decomposition (DMD), Sparse Identification of Non-linear Dynamics (SINDy), Koopman Operator, etc., and their 
implementations. SINDy has been implemented as the python package PySINDy and, while effective, requires considerable 
knowledge in Python programming to utilise the tools to their full extent. `SEED` remedies this barrier by providing
a Graphical User Interface (GUI) with access to all facets of PySINDy while remaining approachable and easy to use.

`SEED` provides a modular approach for interfacing with PySINDy. One may choose from a selection of differentiation 
methods, optimiser methods and custom libraries and can change any options within these categories, with typical default values
provided. `SEED` then creates the SINDy model and provides the output equations and model comparisons, which can then be 
saved for use. SINDy with Control (SINDYc) functionality is also provided to allow the user to identify dynamical systems
with forcing inputs and control.

# References