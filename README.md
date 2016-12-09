# Introduction
`Beiwe-Analysis` is our GitHub code repository for analyzing Beiwe and collaborator data.  Some of this code references **`Python`** or **`C`**-related code for speed, but most of this code is in **`R`**, and is readily converted into an **`R`** package.

This is largely an effort of Ian and Patrick, but we intend to include any other efforts as well.  These efforts are closely related to Matt's `beiwedata`, and we plan to merge our efforts in the future.

# Table of Contents
- [Overview](#Overview)
    - [Preprocessing](#Preprocessing)
    - [Processing](#Processing)
    - [Outputs](#Outputs)

## Overview
![beiwe_analysis_overview](https://github.com/onnela-lab/Beiwe-Analysis/blob/master/Figures/beiwe_analysis_overview.png)
## Preprocessing
Beiwe data comes in [standard formats](https://github.com/onnela-lab/beiwedata#data-overview), but requires processing before generating any insights.  This includes the most basic tasks, such as determining how much data you have, or its quality.  Also, our collaborators usually have separate data they would like to combine with Beiwe data.  It is not obvious how all of this should be done.

We say data is ***preprocessed*** if it takes the form of a two-dimensional array (*i.e.* matrix, data frame) with at least two columns:
* **`Datetime`**, a string containing a universal format for date and time.  For now, it's a **`POSIXct`** object, but this may change.
* **`Person`**, a string containing an ID for the subject at hand.

The goal of preprocessing with raw Beiwe data or collaborator is to convert it to processed data.

## Processing
Processing 
## Outputs




