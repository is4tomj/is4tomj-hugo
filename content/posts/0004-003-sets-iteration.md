---
title: "Strict Antecedent Basis: Sets and Iteration"
description: "Working with sets of objects and iterating through a set of objects."
date: "2016-10-28"
lastmod: "2016-10-31"
categories: 
    - "Strict Antecedent Basis"
    - "Drafting"
    - "Patent Application"
    - "Claims"
    - "Critical Skill"
---


## Sets

__**Attention**__: courts may construe a "set" of objects as two or more objects. Construing sets to mean two or more is a ridiculous interpretation because one skilled in the art of software knows that a set can comprise zero or more objects. One solution is to include the following in the specification:

> A "set" may comprise zero, one, or two or more elements.

## The First rule of sets — do not use sets

Sets often create confusion. Do not use a set unless a set is required.

In many cases, you can use one or two objects rather than a set. Referencing multiple references for multiple objects is usually clearer and broader than using sets. The following is an example:

``` claim
doing a first thing with a first object;
doing the first thing with a second object;
```

## Second rule of sets – if using a set is required, then do not use "respectively" language

A claim that uses a set often uses "respectively" haphazardly, and often incorrectly, throughout the claim. If two sets are needed, and each object in a first set is related to a corresponding object in a second set, then consider doing the following:

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
 

## Iterative blocks

Iterating over a plurality of things leads to tricky claim language. When iterating over a set is required, perform the iteration with an iterative block. The following is an example of an iterative block that performs two actions on each object in a set:

``` claim
for each thing among a plurality of things:
  doing a first action with the thing;
  doing a second action with the thing;
```

In this example, the claim is iterating over a set—the plurality of things— and doing a first action and a second action with the thing from the plurality of things in the current iteration.

An iterative block may be a single line. For example, the following is an example of an iterative block that is a single line. The scope, which is discussed further herein, is just the single line.

``` claim
for each thing among a plurality of things, doing an action with the thing; 
```

## Scope and iterative blocks

The keyword phrase `each`, unlike any of the other keyword phrases that instantiate a noun phrase, instantiates a noun phrase for an object only within the scope of the iterative block.  The following is an example that violates this rule.

``` claim
for each thing among a plurality of things:
  doing a first action with the thing; 
  doing a second action with the thing;
creating a particular widget;
doing a third action with the thing and the particular widget;
```

As seen in the example above, the reference to the thing in the last line is nonsensical, because the reference to the thing in the last line is outside the scope of the iterative block.

## Multiple iterative blocks

### Nested blocks

More is coming.
