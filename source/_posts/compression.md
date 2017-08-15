---
title: Compression
date: 2017-08-15 12:21:10
tags: #conscience
---

Any definition of conscience, and therefore intelligence, should somehow incorporate the amount of compression that the agent applies to its senses. In a way compression is the same as understanding in the following way. Suppose we have a sequence of data points, for example the sequence of even numbers. A priori this contains an infinite amount of information, which is impossible to store. But by employing patterns in the data, we can make a finite representation: informally "start at 0 and keep on adding +2". 

Depending on the expressive strength of the agents internal language we can build representations of more complex data[^1]. Depending on the reasoning capacity the agent can then find and exploit more and more patterns in the data allowing for efficient representation.

In practice an agent might be supplied some initial segment of a sequence, i.e. the observations of the first 100 even numbers. Using some form of (probabilistic[^2]) reasoning the agent builds an efficient representation as the informal sentence above. But not only is the data compressed by this, the agent also gains predictive power over future elements of the sequence. 

This analogy between compression and understanding cuts both ways. For example by recognizing the depicted objects on a painting, I am at the same time also compressing my internal representation of the painting.

[^1]: The upper bound on the expressive strength, assuming that brains are essentially Turing machines, is storing a representation in some sentence of a Turing complete language.

[^2]: Of course the agent will associate some form of probability that this representation is correct.
