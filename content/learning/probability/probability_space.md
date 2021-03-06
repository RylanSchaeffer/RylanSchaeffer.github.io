# Probability Spaces

__Parent__: [Probability](../probability.md)

## Definition

A probability space is a 3-tuple consisting of

1. A set $$X$$ called the sample space i.e. the set of all possible outcomes
2. A [$$\sigma$$-algebra](sigma_algebra.md) on the set $$X$$, which informally tells us all the
   possible ways to think about sets of possible outcomes
3. A [probability measure](probability_measure.md) $$P$$ 

Intuitively, the sample space gives us all possible outcomeshe $$\sigm
   
A collection $$C$$ of subsets of set $$X$$ is
called a __$$\sigma$$-algebra__ on $$X$$ if

1. X belongs to C i.e $$X \in C$$
2. C is closed under complementation. That is, if $$c \in C$$, then $$\overline{c}
   := X \ c \in C$$
3. C is closed under countable unions. That is, if $$c_1, c_2, ... \in C$$, then
   $$\cup_{i=1}^{\infty} c_i \in C$$


## Related Material

A __measurable space__ (also called a Borel space) is a 2-tuple consisting of

1. A set $$X$$
2. A A [$$\sigma$$-algebra](sigma_algebra.md) on the set $$X$$

When the 2-tuple measure space is equipped with a measure $$\mu$$, becoming a 3-tuple,
the measurable space becomes a __measure space__.