# VCAATrollSheet
A demonstration on how to abuse Mathematica almost as much as VCAA was abused as a kid.

## What is this?
###### A message from Sai
Originally designed as a bound reference for a computer based exam, I decided to explore the uses of Mathematica not just as a CAS (Computer Algebra System) but also as a programming language. In learning to use the Wolfram language, I discovered that you can import Wolfram language files (.wl for short) from your computer, similar to importing a python library, be it from your local file or elsewehere.

## What can you do with this?
The ultra sheet package streamlines VCAA questions that are often tedious to do. For example, need to know what a graph looks like with all intercepts and turning points? Well UltraPlot can do that for you. Need quick and easy conversions between degrees and radians? Then ToDeg and ToRad are your new best friends. Need to complete the square because VCAA are archaic morons? A precompiled Compsq function laughs in VCAA's faces giving flashbacks to their abraised childhood. To top that all off, a comprehensive help function has been implimented so even a VCAL student might be able to pick this package up.

Our glorious leader Papa Sai has even been kind enough to lend us his MASTER cheatsheet, which covers a majority of topics a mathematically minded VCE student might face now, and in the future.

## How do I load the VCAA hacks into Mathematica?
First download the above files by clicking the green button on the top left and downloading as a zip. Please note that myself and Sai will update this package periodically with improovements and expansions to show VCAA who has the high ground, so check back every now and then and see if the version number increases. Once the file is downloaded, unpack it (google how to unpack zip file if unsure) and store it somewhere you know the file directory of (e.g desktop). Launch mathematica, and enter: 
    Get["directory of ultrasheetworking.wl"]
Press shift+enter and boom, the package will stay loaded until that session of Mathematica is closed. At the start of an exam, for example, take a USB with ultrasheet on it, load it in using the same method as above and feel free to abuse Mathematica as much as you wish.  

To get started with learning how this library works, type the command Help[] for a comprehensive guide on its ability.

## General Notes
If you want to tinker with the package, do not open the Wolfram Language file. This is because images and cell expressions are not compressed and stored effeciently, meaning your kernel may crash. To do so, open the UltrasheetCode.nb and after editing, save the file as a Wolfram language file.

Furthermore, help is always appriciated! If you've got some kickass Mathemtica function and an inner desire to abuse VCAA's idiocy, contact Sai and Kade over GitHub, or create a pull request. 

Regards,
Sai Kumar Murali Krishnan & Kade Bamford
