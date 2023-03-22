---
layout: default
title: Uses and Applications
nav_order: 7
---
# What can you do with TEI?

TEI is highly flexible, and encoded documents can be used in many ways: for digital presentation (such as digital editions of texts), programmatic analysis, enabling linked data, text searching in databases, and more. All this is enabled by the _structured_ nature of TEI, and the human- and computer-readability of encoded texts. This allows other programs and scripts to then turn an encoded text into much more. 

One of the major strengths of TEI and why it is used so much in research projects is that it is designed to be shared. Researchers can take someone’s TEI file and enrich it, for example by adding extra detail or transcriptions. Doing this kind of encoding also turns text into manipulable data. Because TEI XML separates the structure of a text from the content it’s possible to present the text in many different ways and manipulate it in the course of working with it for example by subsetting it in order to visualize an idea that is present in the text. 

XML file formats are also very durable. Because of the low dependencies on other technologies that TEI XML has these types of documents can last a long time and machines should be able to read them. Only ASCII and SGML need to continue to exist into the future. All digital files are prone to quite fast rates of decay but having them structured in a way that makes them very simple and replicable helps to buffer against that. 

As has been noted, TEI is based in XML which is extensible, it can grow over time or even within the scope of a single project. It isn’t system or device dependant. It’s a dominant information interchange format on the internet. both machine-readable and human-readable. This means that a computer can identify and interpret the markup, but a human can as well. For example, using the element <language ident="en-GB"> tells to computer that the item is in British English – but it’s also relatively easy to see that it’s about language and the codes are intelligible.

## Examples of applications

### Example 1: [Text encoding for Baroness Elsa von Freytag-Loringhoven (Tanya Clement, 2009)](https://digital.lib.umd.edu/transition/index.html)

This example uses poems written by the excentric German-American writer Baroness Elsa von Freytag-Loringhoven. The project created by Tanya Clement in 2008 takes the .tiff scans of the original, handwritten poem and compares it to a reworked second version of the poem. The encoded transcriptions make it possible to compare line changes--for example.

### Example 2: [Wilde Trials International News Archive](https://dhil.lib.sfu.ca/wilde/index.html)

Here we see newspaper transcriptions, in various languages, of the Wilde trials. The goal of this project was to compare similarities iin either language and to search transcriptions. 

### Example 3: [Colonial Despatches](https://bcgenesis.uvic.ca/index.html)

In this example, the goal was to make a direct comparison between the scanned image and transcription. 

### Example 4: [Map of London](https://mapoflondon.uvic.ca/)

The Map of London seeks to identify landmarks and find resources for each landmark.


## Recap: advantages of TEI

* Human and computer-readable: E.g. using the element `<language ident="en-GB">` tells to computer that the item is in British English – but it’s also relatively easy to see that it’s about language and the codes are intelligible.
* XML documents are easily shared. Researchers can take someone’s TEI file and enrich it, for example by adding extra detail or transcriptions. 
* TEI documents are easy to reproduce and can be more easily preserved than other types of more complex documents.
* The structured nature of TEI records means (at least in theory) that records can be worked with at scale to support big data analysis or text data mining.
