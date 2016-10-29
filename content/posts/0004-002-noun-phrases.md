---
title: "Strict Antecedent Basis: Noun Phrases"
description: "Instantiating and referencing noun phrases."
date: "2016-10-27"
lastmod: "2016-10-28"
categories: 
    - "Strict Antecedent Basis"
    - "Drafting"
    - "Patent Application"
    - "Claims"
    - "Critical Skill"
---

## Noun phrases -- the building blocks of clear claim language

A noun phrase is a word or group of words that functions in a sentence as subject, object, or prepositional object. A noun phrase in a claim should be clearly defined so that future references to the noun phrase are easily recognized.

### Instantiating a noun phrase

A noun phrase should be instantiated only once in a claim using one keyword phrase among a set of instantiating keyword phrases:

- `a`,
- `an`,
- `one|two|𝑥`,
- `at least`,
- `each`.

The following are examples of instantiating a noun phrase with a keyword phrase from the set of instantiating keyword phrases:

- `a first thing`,
- `a second thing`,
- `a plurality of things`,
- `one or more things`,
- `two or more things`,
- `three or more things`,
- `at least one thing`,
- `at least two things`.

The `each` instantiating keyword phrase is a special keyword phrase that is discussed in [Sets and Iteration]({{< ref "0004-003-sets-iteration.md" >}}).

### Referring to an instantiated noun phrase

 After a noun phrase is instantiated, the `the` keyword phrase should be used to reference the noun phrase exactly as the noun phrase is instantiated. The following are examples of referring to an instantiated noun phrase:

- `the first thing`,
- `the second thing`,
- `the plurality of things`,
- `the one or more things`,
- `the two or more things`,
- `the three or more things`,
- `the at least one thing`,
- `the at least two things`.

A noun phrase should not be referenced using a modifier, such as an adjective.  For example, if a claims includes `receiving a thing`, then `the thing` should **not** be referenced as `the received thing` in the claim.

### A noun phrase references an immutable object

A noun phrase references an object that is immutable. If the object is modified, then the object is a new object.  Accordingly, a new noun phrase should be instantiated to represent the new object.  The following is an example of assigning a new noun phrase to a modified object:

``` claim
1. A method comprising:
  receiving a first thing;
  modifying the first thing to produce a second thing.
```

Do not make a noun phrase ambiguous by referring to two objects with the same noun phrase.  The following is an example of a claim that creates an antecedent basis error by using a single noun phrase to reference two objects with different states: 

``` claim
1. A method comprising:
  receiving a thing that includes a partiuclar component;
  modifying the particular component included in the thing;
  sending the thing to a person.
```

The following claim is free of antecedent basis errors by assigning a new noun phrase to a modified object:

``` claim
1. A method comprising:
  receiving a first thing that includes a particular component;
  producing a second thing from the first thing by modifying the particular component;
  sending the second thing to a person.
```