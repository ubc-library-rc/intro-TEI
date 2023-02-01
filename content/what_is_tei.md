---
layout: default
title: What is TEI?
nav_order: 6
---
# What is TEI?

TEI stands for: the Text Encoding Initiative, a “consortium which collectively develops and maintains a standard for the representation of texts in digital form” (https://tei-c.org/). 

TEI is actually three things: 

- it is a set of **guidelines** that the Text Encoding Initiative developed for describing text based objects (eg. manuscripts, archives, letters, newspapers)
- it is an **organisation** which oversees the production of official guidelines
- it is a **community of practice** of people using the guidelines

## Markup

TEI is one kind of **mark up language**.  

Markup encodes information about text – it could describe the structure, appearance and content of a text. Digital markup has to be explicit and unambiguous so that a computer can understand it.

Markup can be:

- **presentational** (it gives instructions on how a text appears on the page eg. line breaks, tabs etc.), 
- **procedural** (it gives an output device, for example a printer, information about how it should deal with text) or 
- **descriptive** (it encodes the structure of the text, but not what to do with it)

(Adapated from Coombs, James H., Allen H. Renear, and Steven J. DeRose. 1987. "Markup Systems and the Future of Scholarly Text Processing." 
in (Landow and Delaney 1993))

TEI is **based on XML** (eXtensible Markup Language), which is a **descriptive** markup language. EAD (encoded archival description), 
used to describe archival materials, also uses XML. 

### XML

Since TEI is based on XML, here are two things you should know about XML:

* XML is non-proprietary and does not depend on a specific piece of software to use it
* XML has basic rules and structure that TEI inherits and need to be followed
* XML describes data and information, but does not instruct how it appears on the page
* XML is human and computer readable

## Another look at TEI and XML

Another way to understand the relationship between TEI and XML is to think of TEI as a language (it is an encoding language after all). TEI provides terms we can use such as ```<body>``` or ```<p> (paragraph)``` or ```<speaker>```. These guidelines were developed to better enable scholars to share and communicate in a common language about texts. That said, TEI is also customizable and is flexible enough to be used for all sorts of documents.

XML, on the other hand, is a metalanguage. It describes how markup languages operate, of which TEI is one. XML provides a set of rules for how those languages can be used.
