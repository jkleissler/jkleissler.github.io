---
layout: post
title: Assignment 3
date:   2016-07-13 19:45:31 +0530
categories: Assignment 3 Post, science
---

This post is in regards to Assigment 3 for INLS 161. The objective of the assignment is to write a script, using pandoc, that will convert files from one formtat to another depending on your selection. For this assignment a .md file should be converted to a .doxc, .pdf, .hmtl, and .otd files. The file in said assignment is a paper of mine I wrote for another course I am currently taking, it is simply tiled Assignment-3-paper.md for the purpose of the assignment but it is an evaluation and critique of Peter Singer's moral theory. Back to what is acctually going on within the program when the script is running. pandoc is the command being utilized in order to convert the file types. For the program to know what file is being converted the comman -o is employed, which stands for output. A variable will follow, $INPUTFILE, and ending with the desired file type. This step is repeated until the goal of creating all file types is in place. Once that is finilized we must install TeXLive in order to convert any file type into a .pdf, once that is done everything should run smoothly.

Here are the resulting files:

[Original File](https://github.com/inls161/assignment-3-convert-some-documents-jkleissler/blob/master/Assignment-3-paper.md)

[HTML File](https://github.com/inls161/assignment-3-convert-some-documents-jkleissler/blob/master/Assignment-3-paper.html)

[OTD File](https://github.com/inls161/assignment-3-convert-some-documents-jkleissler/blob/master/Assignment-3-paper.otd)

[DOCX FIle](https://github.com/inls161/assignment-3-convert-some-documents-jkleissler/blob/master/Assignment-3-paper.docx)

[PDF File](https://github.com/inls161/assignment-3-convert-some-documents-jkleissler/blob/master/Assignment-3-paper.pdf)
