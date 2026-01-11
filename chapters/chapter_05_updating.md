## Chapter 5: Updating

Given that my beliefs should be probabilistic, how should they change when I encounter evidence?

This is not a matter of preference. Once I have accepted the probability axioms, the update rule is fixed.

The reason is that **conditional probability** is defined within the framework. $P(H|E)$—the probability of $H$ given $E$—is defined as $P(H \cap E) / P(E)$, the probability that both $H$ and $E$ hold, divided by the probability that $E$ holds. This is not a separate assumption; it is part of what probability means.

Rearranging this definition yields **Bayes' theorem**:

$$P(H|E) = \frac{P(E|H) \cdot P(H)}{P(E)}$$

Here $P(H)$ is my prior probability of hypothesis $H$ before seeing evidence $E$. $P(E|H)$ is how likely the evidence is if $H$ is true. $P(E)$ is the total probability of the evidence across all hypotheses. And $P(H|E)$ is my posterior probability—my belief in $H$ after seeing $E$.

This is a theorem, not a recommendation. If my beliefs before the evidence are probabilistic, and I want my beliefs after the evidence to be probabilistic, this is how they must relate.

An example: I have two hypotheses about a coin. $H_1$: the coin is fair (50% heads). $H_2$: the coin is biased (90% heads). I start assigning 50% probability to each. I flip the coin and it lands heads. Applying Bayes' theorem, my probability for $H_2$ rises to about 64%. Seeing heads made me more confident the coin is biased, because heads was more likely under that hypothesis. This is how learning works.

Bayes' theorem tells me how to update. But it requires a starting point—a prior probability before any evidence. Where do priors come from?

### Historical and Philosophical Context

Bayes' theorem is named for Thomas Bayes, who proved a version of it posthumously published in 1763. Pierre-Simon Laplace independently developed and extensively applied the result. The interpretation of probability as degree of belief, and Bayesian updating as the rational response to evidence, was developed systematically in the 20th century by Ramsey, de Finetti, Savage, and Jaynes, among others.
