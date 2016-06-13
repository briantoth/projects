---
layout: page
title: Projects
---
{% include JB/setup %}

## Current Projects

### Draftomatic

[Draftomatic](https://github.com/MageRings/draftomatic) is a swiss pairing system which optimally determines pairings given the following rules:

1. Players may leave the tournament at any time
1. Players may win, lose, or draw matches
1. There must be exactly N rounds
1. No two players may play each other more than once
1. Assuming that the players are ranked, pairings should follow this ranking
(first ranked plays second ranked, etc.) to the greatest extent possible (minimize deviation)

The solution is found with a reduction to a graph problem that can be solved by [Choco](http://choco-solver.org/), a library for constraint programming.

### evil-eye-of-ohseaar

[evil-eye-of-ohseaar](https://github.com/briantoth/evil-eye-of-ohseaar) is a system for digitizing collections of Magic: the Gathering trading cards.
The code uses [OpenCV](http://opencv.org/) for image processing, [tesseract](https://github.com/tesseract-ocr/tesseract) for OCR, and [pHash](http://www.phash.org/)
for image comparison.  The physical component of the system consists of a modified card shuffler controlled by an [Arduino](https://www.arduino.cc/).

## Past Projects

### GQL Implementation for Pouchdb

GQL ([Google Query Language](https://developers.google.com/chart/interactive/docs/querylanguage)) is a SQL-like language for performing queries.
For those familiar with more traditional databases, it can be easier to understand than [PouchDB](https://pouchdb.com/)'s native MapReduce syntax.
I wrote a simple transpiler that generates PouchDB queries from GQL queries, using the ideas found [here](http://javascript.crockford.com/tdop/tdop.html).

The original pull request can be found [here](https://github.com/pouchdb/pouchdb/pull/478/files), but the code now lives [in its own repository](https://github.com/pouchdb/GQL).

I also wrote a series of [introductory articles](https://briantoth.github.io) for Pouchdb.

### ECE 4760 Final Project

My final project for the microcontrollers course at Cornell involved providing localized directions using a remote GPS unit
informed by a remote base station. Full details and source code can be found [on the department website](https://people.ece.cornell.edu/land/courses/ece4760/FinalProjects/s2012/bdt25_edr46/bdt25_edr46/index.html).

