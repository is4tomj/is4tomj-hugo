---
title: "Strict Antecedent Basis: Sets and Iteration"
description: "Working with sets of objects and iterating through a set of objects."
date: "2016-10-28"
categories: 
    - "Strict Antecedent Basis"
    - "Drafting"
    - "Patent Application"
    - "Claims"
    - "Critical Skill"
---


## Sets

__**Attention**__: courts may construe a "set" of objects as two or more objects. This is a ridiculous interpretation because any one skilled in the art of software knows that a set can comprise zero or more objects. One solution is to include the following in the specification:


> A "set" may comprise zero, one, or two or more elements.

## First rule of Sets — do not use sets

Sets often create confusion. Do not use a set unless a set is required.

In most cases, use one or two objects. Using referencing multiple objects individually makes a claim clearer and broader. The following is an example:

``` claim
doing a first thing with a first object;
doing the first thing with a second object;
```

## Second rule of Sets – if using a set is required, then do not use "respectively" language

A claim that uses a set will frequently use "respectively" haphazardly, and often incorrectly, throughout the claim. If two sets are needed, and objects in a first set are related to a corresponding object in a second set, then consider doing the following:

``` claims
A method comprising:
  ... a first set of objects;
  ... a second set of objects;
  wherein each object in the first set of objects has a corresponding object in the second set of objects;
  ...
  selecting a particular object from the first set of objects;
  ...
  performing a step with the particular object and the corresponding object.
```
 

## Iterating through a set

Iterating over a plurality of things frequently leads to tricky claim language.

``` claim
for each thing among a plurality of things:
  doing a first action with the thing; 
  doing a second action with the thing;
```

More is coming here.