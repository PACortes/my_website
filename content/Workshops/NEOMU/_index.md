---
date: "2022-08-10"
linkTitle: NEOM
summary: In this workshop we will introduce the R software. We will learn basic tools for data visualization and analysis. Finally, we will learn how to create automatic reports.
title: "NEOM ERI-U-TA"
type: book
---

{{< figure src=“NeomLogo.png” >}}

{{< toc hide_on=“xl” >}}

## About this Workshop

The aim of this five-day introductory workshop is to guide you through the basics of using `R` via `RStudio` for analysis of institutional data. It is ideal for people new to R or who have limited experience.

I assume no prior coding language for this workshop. My goals are to equip you to work comfortably from the RStudio environment, process, and explore data, and make very nice graphical representations of data.

Specific topics covered include the R environment (directories, workspace, scripts, and packages), data structures (vector, matrix, data frames, lists), and data visualization (scatterplots, boxplots, histograms, etc.).

## ¿What is `R`?

`R` is a language and software environment for statistical computing and graphics.

R provides a wide variety of statistical and graphical techniques, and is highly extensible.

It is one of the most popular languages used by statisticians, data analysts, researchers and marketers to retrieve, clean, analyze, visualize and present data.

## The `R` software environment

The R language programming environment is a fully planned and coherent system built around a standard command-line interface. Users leverage this to read data and load it to the workspace, specify commands and receive results.

## Why use `R`?

-   R is open-source and free!

-   R is popular and R community is huge

-   R runs on all platforms (Available for Windows, Macintosh, and Linux).

-   Publication-quality graphs. With R you have complete control over plotting/graphing options and are able to output publication quality figures with ease.

-   Packages for *literate statistical programming* - weaving written reports and analysis code in one document.

-   It's fun... probably not at the beginning of the learning process.

    ![Credit: @allison_horst](r_rollercoaster.png)

The R language programming environment is a fully planned and

## ¿What is `RStudio`?

`RStudio` is a free, open source IDE (integrated development environment) for R. Its interface is organized so that the user can clearly view graphs, data tables, R code, and output all at the same time. It also offers an Import-Wizard-like feature that allows users to import *CSV*, *Excel*, *SAS*, *SPSS* and *Stata* files into R without having to write the code to do so.

It is important to note that `RStudio` is a software that runs `R` and provides additional tools that are useful when writing `R` code. So `R` and `RStudio` are not the same.

## Definitions

The following concepts will be helpful as you begin to explore the `R` world.

**CRAN**: The Comprehensive R Archive Network is a network of web servers around the world that store identical, up-to-date, versions of code and documentation for R.

**R packages**: Extensions to the R programming language. R packages contain code, data, and documentation in a standardised collection format that can be installed by users of R, typically via a centralised software repository such as CRAN. The location where the packages are stored is called the library. If there is a particular functionality that you require, you can download the package from the appropriate site and it will be stored in your library.

**Function**: is a set of statements organized together to perform a specific task. R has a large number of in-built functions and the user can create their own functions.

## Installing and Loading Packages

In order to use a package, it needs to be installed on your computer by running `install.packages("name_of_package")` (do not forget `""` around the name of the package).

Once the package is installed, you must load the package and only after it has been loaded you can use all the functions and datasets it contains. To load a package, run `library(name_of_package)` (this time `""` around the name of the package are optional).
