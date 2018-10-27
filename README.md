# VCAATrollSheet
A demonstration on how to fully abuse Mathematica for a computation based exam.

## What is this?
Originally designed as a bound reference for a computer based exam, I decided to explore the uses of Mathematica not just as a CAS (Computer Algebra System) but also as a programming language. In learning to use the Wolfram language, I discovered that you can import Wolfram language files (.wl for short) from your computer, similar to importing a python library, be it from your local file or elsewehere.

## What can you do with this?
The ultra sheet package has several shortcut functions for particularly long names. For example, NormalDistribution is abbreviated to ND[mean,S.D] and so on. In addition, several custom functions have been designed, for instance VecPlot lets you plot two-dimensional vectors in an {i,j} space while UltraPlot labels endpoints, stationary points and more. 

The master cheat sheet simply provides documentation on how to use functions for certain topics. It contains functions needed to model or solve certain situations in a test.

## How do I load this into Mathematica?
Use the Get function and add the directory of where you downloaded the ultrasheetWorking.wl file. Enter Get["Location of ultrasheetWorking.wl"] and the package will be loaded into Mathematica for the session. To get help, do Help[] and a guide will pop up with documentation on how to use the package.

## General Notes
If you want to tinker with the package, do not open the Wolfram Language file. This is because images and cell expressions are not compressed and stored effeciently, meaning your kernel may crash. To do so, open the UltrasheetCode.nb and after editing, save the file as a Wolfram language file.
