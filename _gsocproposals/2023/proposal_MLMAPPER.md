---
title: Machine Learning Model for the Albedo of Mercury
layout: gsoc_proposal
project: MESSENGER
year: 2023
organization:
 - Alabama
 - Georgia
 - JHUAPL
 - NTUA
---

## Description

The goal of the project is to use machine learning techniques to identify relationships between planetary mapped datasets, with the goal of providing deeper understanding of planetary surfaces and to have predictive power for planetary surfaces with incomplete datasets.

Planetary surfaces are observed as all electromagnetic wavelengths (e.g. radar, infrared, optical, ultraviolet, x-ray, gamma-ray), and each wavelength provides unique information about the chemistry, mineralogy, and history of the surface. Yet the information is not entirely independent. For example, the chemical element iron, which is mapped with x-rays and gamma rays, is highly related to optical albedo on the Moon. Knowing this, we can develop high-spatial resolution predictive maps of iron based on optical data. On other planets, the relationships between the observations are less well know, and indeed some datasets are missing.

We seek to study planetary surfaces by inputting maps of surfaces at all wavelengths available to discover the relationships between the measurements and to make predictions about chemistry that are not directly sampled by observations. This provides a way of studying the geologic history of a planet with existing data, which is valuable given the infrequent opportunities for new measurements by planetary spacecraft.

## Duration

Total project length: 175 hours.

## Task ideas
  * Implement a deep multi-objective regression model to predict the chemical composition of Mercury based on data collected by the Messenger mission.

## Expected results
  * Accurate models of albedo and chemical composition based on Messenger mission data

<!-- ## Test

Please use [this link](https://drive.google.com/file/d/1QoxSdeL0JOqJJKCea75AwIyaujIV8gxB/view?usp=sharing) to access the test for this project. -->

## Requirements 
Python, previous experience in Machine Learning. 


## Mentors

  * [Patrick Peplowski](mailto:ml4-sci@cern.ch) (JHUAPL)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Jason Terry](mailto:ml4-sci@cern.ch) (University of Georgia)
  * [Giorgos Pipilis](mailto:ml4-sci@cern.ch) (NTUA)


 
Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.
