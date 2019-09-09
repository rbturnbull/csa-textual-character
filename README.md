# The Textual Character of Codex Sinaiticus Arabicus and its Family
![Ancient vs. Byzantine - 4 Gospels](../../blob/master/Graphs/Ancient-Byz-4Gospels-Colour.svg)

This repository includes data and code to accompany my paper 'The Textual Character of Codex Sinaiticus Arabicus and its Family' which I delivered at the 11th [Birmingham Colloquium on the Textual Criticism of the New Testament](https://www.birmingham.ac.uk/research/activity/itsee/events/bham-colloquium.aspx) in March, 2019. The print version of the paper is forthcoming.

## Collation Results
The following CSV files contain the collation results when comparing Arabic Family B with the Greek readings of Text und Textwert. The first column is the Teststelle number. The second column is the Arabic text. The 3rd column are the labels for the variant readings which the Arabic could potentially derive from. Arabic words in square brackets are given to indicate context. Arabic words in braces indicate conjectures of the presumed meaning if the text isn't clear.

* [Matthew](../../blob/master/FamilyB-TextUndTextwertCollation.Matthew.csv)
* [Mark](../../blob/master/FamilyB-TextUndTextwertCollation.Mark.csv)
* [Luke](../../blob/master/FamilyB-TextUndTextwertCollation.Luke.csv)
* [John](../../blob/master/FamilyB-TextUndTextwertCollation.John.csv)

## Quantifying Similarity

There is a Python notebook which demonstrates how to implement and use some of the formulas that I discuss in the paper. A [static version is available on Github](../../blob/master/QuantifyingSimilarity.ipynb) and an [interactive version can be opened here or in Google Colab](https://colab.research.google.com/github/rbturnbull/csa-textual-character/blob/master/QuantifyingSimilarity.ipynb).
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rbturnbull/csa-textual-character/blob/master/QuantifyingSimilarity.ipynb)


## Ranking Greek Manuscripts
Here are the full rankings of all the Greek manuscripts (attesting more than 10) of Text und Textwert with Arabic Family B. 
### All Teststellen
* [Matthew](../../blob/master/FamilyB-MssSimilarities-AllTeststellen.Matthew.csv)
* [Mark](../../blob/master/FamilyB-MssSimilarities-AllTeststellen.Mark.csv)
* [Luke](../../blob/master/FamilyB-MssSimilarities-AllTeststellen.Luke.csv)
* [John](../../blob/master/FamilyB-MssSimilarities-AllTeststellen.John.csv)

### Non-Byzantine Teststellen
These similarities are restricted to the Teststellen where Arabic Family B unambiguously attests a non-Majority Text variant.
* [Matthew](../../blob/master/FamilyB-MssSimilarities-NonByzantineTeststellen.Matthew.csv)
* [Mark](../../blob/master/FamilyB-MssSimilarities-NonByzantineTeststellen.Mark.csv)
* [Luke](../../blob/master/FamilyB-MssSimilarities-NonByzantineTeststellen.Luke.csv)
* [John](../../blob/master/FamilyB-MssSimilarities-NonByzantineTeststellen.John.csv)


## Graphs

The paper includes several graphs. Here are colour versions as well as other graphs omitted for the sake of space.

### Ancient vs. Byzantine
![Ancient vs. Byzantine - Matthew](../../blob/master/Graphs/Ancient-Byz-Matthew-Colour.svg)
![Ancient vs. Byzantine - Mark](../../blob/master/Graphs/Ancient-Byz-Mark-Colour.svg)
![Ancient vs. Byzantine - Luke](../../blob/master/Graphs/Ancient-Byz-Luke-Colour.svg)
![Ancient vs. Byzantine - John](../../blob/master/Graphs/Ancient-Byz-John-Colour.svg)
![Ancient vs. Byzantine - 4 Gospels](../../blob/master/Graphs/Ancient-Byz-4Gospels-Colour.svg)

### Special vs. Byzantine
![Special vs. Byzantine - Matthew](../../blob/master/Graphs/Special-Byz-Matthew-Colour.svg)
![Special vs. Byzantine - Mark](../../blob/master/Graphs/Special-Byz-Mark-Colour.svg)
![Special vs. Byzantine - Luke](../../blob/master/Graphs/Special-Byz-Luke-Colour.svg)
![Special vs. Byzantine - John](../../blob/master/Graphs/Special-Byz-John-Colour.svg)
![Special vs. Byzantine - 4 Gospels](../../blob/master/Graphs/Special-Byz-4Gospels-Colour.svg)

### Byzantine vs. Time

![Byzantine vs. Time - Matthew](../../blob/master/Graphs/Byz-Time-Matthew-Colour.svg)
![Byzantine vs. Time - Mark](../../blob/master/Graphs/Byz-Time-Mark-Colour.svg)
![Byzantine vs. Time - Luke](../../blob/master/Graphs/Byz-Time-Luke-Colour.svg)
![Byzantine vs. Time - John](../../blob/master/Graphs/Byz-Time-John-Colour.svg)
![Byzantine vs. Time - 4 Gospels](../../blob/master/Graphs/Byz-Time-Gospels-Colour.svg)

### Ancient vs. Time

![Ancient vs. Time - Matthew](../../blob/master/Graphs/Ancient-Time-Matthew-Colour.svg)
![Ancient vs. Time - Mark](../../blob/master/Graphs/Ancient-Time-Mark-Colour.svg)
![Ancient vs. Time - Luke](../../blob/master/Graphs/Ancient-Time-Luke-Colour.svg)
![Ancient vs. Time - John](../../blob/master/Graphs/Ancient-Time-John-Colour.svg)
![Ancient vs. Time - 4 Gospels](../../blob/master/Graphs/Ancient-Time-Gospels-Colour.svg)

### Special vs. Time

![Special vs. Time - Matthew](../../blob/master/Graphs/Special-Time-Matthew-Colour.svg)
![Special vs. Time - Mark](../../blob/master/Graphs/Special-Time-Mark-Colour.svg)
![Special vs. Time - Luke](../../blob/master/Graphs/Special-Time-Luke-Colour.svg)
![Special vs. Time - John](../../blob/master/Graphs/Special-Time-John-Colour.svg)
![Special vs. Time - 4 Gospels](../../blob/master/Graphs/Special-Time-Gospels-Colour.svg)


