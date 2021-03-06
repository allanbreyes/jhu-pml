# Practical Machine Learning

## About

This repository contains coursework completed while taking Johns Hokpins' **Practical Machine Learning** class on [Coursera](https://class.coursera.org/predmachlearn-011).

## Introduction

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit, it is now possible to collect a large amount of data about personal activity relatively inexpensively.  These type of devices are part of the quantified self movement--a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech enthusiasts.  One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. Participants were asked to perform barbell lifts correctly and incorrectly in 5 different ways.  In this project, the goal was to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants to predict the manner in which they did their exercise.

## Data

The data for this project came from [Groupware@LES](http://groupware.les.inf.puc-rio.br/har), and is available in CSV format, partitioned into training and test datasets, in the `data/` directory.

## Analysis

The analysis is viewable in two formats:

- **R Markdown**: `pml.Rmd` (recommended)
- **Viewable HTML**: `index.html` or hosted on [GitHub pages](http://allanbreyes.github.io/jhu-pml/index.html)

## Results

The machine learning algorithm used was a *random forest classifier*, and produced flawless accuracy in prediction of the 20 tests.