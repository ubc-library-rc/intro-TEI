---
layout: default
title: Introduction
nav_order: 4
---
# Introduction

## Encoding and Land
As an entry point into text encoding, let's think about a landmark which represents the ongoing presence of the xwməθkwəy̓əm (Musqueam), Skwxwú7mesh (Squamish), Stó:lō and Səl̓ílwətaʔ/Selilwitulh (Tsleil- Waututh) Nations. 

Someone might describe one landmark in this way: 

```sh
 I will be biking past the Welcome Figure underneath Burrard Bridge on the Sea Wall today.
```
If you have a lot of these statements--a bigger dataset or a longer text--you might be interested in an easier way of generating a list, say, of all landmarks in Vancouver which are affiliated with the First Nations, which is difficult to do "manually." Computational power gives you the potential to _encode_ a text in a way that is machine readable. 

```sh
 I will be biking past <placeName> the Welcome Figure underneath Burrard Bridge </placeName> on the Sea Wall today.
```
By adding ```<placeName>``` and ```</placeName>``` we are able to _tag_ a piece of information in a text. With this, we can then generate all the place names we tagged using ```<placeName>``` (we'll talk about the uses for this later). 

As we'll see, there is a great amount of scholarly decision-making and autonomy involved in which tags you choose, which often depends on the goals you hope to accomplish as well as the content you're encoding. Here are some examples of different ways to encode:

```sh
<place>
 <placeName>Abbey Dore</placeName>
 <location>
  <geo>51.969604 -2.893146</geo>
 </location>
</place>
```
```sh
<place xml:id="BGbuilding" type="building">
 <placeName>Brasserie Georges</placeName>
 <location>
  <country key="FR"/>
  <settlement type="city">Lyon</settlement>
  <district type="arrondissement">IIème</district>
  <district type="quartier">Perrache</district>
 </location>
</place>
```
