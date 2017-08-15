---
title: Random
date: 2017-08-15 12:56:09
tags:
---

Intuitively things are only interesting if there is some informational content to them. This can be made formal by using the [Kolomogrov complexity] measure which expresses the size of this information content or complexity. We call the ratio between a sentence's length and its complexity is its compression. So a sentence that compresses well has little complexity.

Unfortunately, using complexity as a measure of value introduces pathologies. The sentences that are least compressible are random sentences (as there are no patterns to exploit). There are information theoretic ways to fix this, nicely [explored by Scott Aaronson][Complexology]. I want to take a different approach and analyse the nature of these random strings.

We essentially deem the random strings to be of no value because they give is no predictive strength over our environment. We say that the information in the string is not (causally) entangled with reality. But is this really the case? Physics teaches us that random strings don't really exists, as von Neumann said:

   Any one who considers arithmetical methods of producing random digits is, of course, in a state of sin. For, as has been pointed out several times,
   there is no such thing as a random number

The random strings in our computer are usually from something physicists call thermal energy. Thermal energy is the micro level jiggling of particles that do not contribute to the macro level state.

Thermal physics teaches us that this thermal energy is not random after all, but degrees of freedom (= information) that has become inaccessible to us. To make this precise: All the thermal energy in a system is in principle enough to allow us to derive all past and future states. But the information is not localized in any structured way so we would need to know all the particles to make sense of it. The inaccessible information is smeared out through all the particles. This is in contrast with accessible information which is localized, like a bit in computer memory.

From this it is clear that randomness is but a matter of perspective, a sufficiently omnipotent being sees no randomness at all, and nature's weather appeared random to earlier humans. 

Accepting that computer randomness is obtained from terminal noise we see that random strings *do* posses a lot of useful information, but it too tangled up to be of any use. This suggests that we should explore the ways in which information is entangled, or to be more specific gives us predictive power, to assess its value.

[Kolomogrov complexity]: https://en.wikipedia.org/wiki/Kolmogorov_complexity
[Complexology]: http://www.scottaaronson.com/blog/?p=762
