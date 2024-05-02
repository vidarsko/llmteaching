# Introduction to large language models

Numerous introductions to large language models exist. 
In order to understand how they can do what they do, and why they are better at certain aspects more than others, it is useful to have a mental model of how they work.
We support the following model:

A large language model is a ship navigating in meaning space.

In the following, we will discuss in how this makes sense, and how it can help you understand the capabilities and limitations of large language models.

## What is meaning space?

The basic functionality of a generative language model consists of encoding words and text in a high-dimensional mathematical space and transforming those vectors.

## Implications

With the ship metaphor in mind, we can deduce several implications. 

* Large language models might generate rubbish. Meaning space is not truth space, and so by looking at the output of a large language model, we can't be sure that it is true. The meaning of training is to determine the currents of meaning space, but the ship can still be lost at sea.
* Large language models can be steered. By providing a prompt, we can guide the ship in a certain direction. This is the basis of fine-tuning.