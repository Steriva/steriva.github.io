---
title: "Indirect Reconstruction of complex fields"
layout: single
collection: research
type: "research"
permalink: /research/IR
excerpt: "<img src='/images/research/IR_cavalleri.png' alt=''>"
order_number: 20
header: 
  og_image: "images/research/IR_cavalleri.png"
---

Reduced Order Modelling in a Data Assimilation framework has become a promising tool to provide quick and efficient state estimations of different fields, assuming to have at disposal measurements of every variable of interest. However, issues arise whenever only partial observations are available, i.e. one or more fields cannot be directly detected because the corresponding sets of sensors are not available. Although the absence of experimental measurements makes the process of data assimilation not possible, investigating the possibility of extracting some indications on the unobserved fields from the observed ones is legitimate, especially for strongly coupled problems. In thermal-hydraulic systems, temperature, pressure and fluid velocity fields are not independent, hence it is not unreasonable to imagine that each of them contains some information about the others. Therefore, the possibility to exploit partial observations on the system in order to reconstruct its whole state should be explored. In this work, it has been decided to focus on the case where only temperature sensors are available, by way of example.

This research work is dedicated to devise the definition of an efficient data-driven method for the reconstruction of the state of a thermal-hydraulic system, where only temperature measurements are taken.
A novel technique has been developed, called **Indirect Reconstruction**, in which a  *non-intrusive* two-step method has been applied to a simple time dependent thermal-hydraulic problem, in order to recover velocity fields from temperature observations. The two different phases are as follows:

1. the estimation of the parameters (PE) characterising the system from the temperature observations, by solving a minimisation problem
2. the reconstruction of the velocity and pressure fields by interpolating the coefficients of the POD reduced basis, exploiting the well established POD-I