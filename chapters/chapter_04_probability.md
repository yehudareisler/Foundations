# Part III: Belief Under Uncertainty

## Chapter 4: Probability

I have beliefs about the world, but I do not have certainty. Some things seem more likely than others. The sun will rise tomorrow: high confidence. It will rain next Tuesday: moderate confidence. There is intelligent life elsewhere in the galaxy: uncertain.

These beliefs come in **degrees**. The question is: are there constraints on how these degrees should behave? Or can I believe whatever I like, with whatever intensity, with no rules?

Some combinations are incoherent. If rain and no-rain exhaust the possibilities, and I am certain one will happen, then my confidence in rain plus my confidence in no-rain should equal my confidence that one or the other will happen. If I assign 90% to rain and 90% to no-rain, I have violated this—I am double-counting my certainty. If I believe A is more likely than B, B more likely than C, and C more likely than A, I have contradicted myself; the "more likely than" relation cannot cycle.

So there must be constraints. What are they?

Here I invoke a mathematical result. Suppose I want my degrees of belief to be **coherent** in the following sense: there is no combination of bets, each of which I find acceptable given my degrees of belief, that guarantees I lose no matter what happens. If my degrees of belief guide my willingness to bet—if believing $P$ with confidence $p$ means I would pay up to $p$ dollars for a bet that pays one dollar if $P$ is true—then incoherent degrees of belief make me a **money pump**.

This is a commitment: I am saying that exploitability in this sense is a failure I want to avoid. One might ask: why care about hypothetical bets I will never actually make? My answer is that being a money pump means my beliefs undermine themselves. If I would accept each of a set of bets but accepting all of them guarantees loss, then my beliefs are not serving their purpose of guiding me toward what I want. This seems like a minimal requirement on beliefs being functional.

The **Dutch Book theorem** states: I am immune to such exploitation if and only if my degrees of belief satisfy the axioms of probability theory. The proof appears in the appendix. What matters here is the consequence: probability theory is not an arbitrary framework. It is the **unique** framework for degrees of belief that avoids this kind of self-defeat.

So my beliefs should be probabilities. But beliefs change when I encounter evidence. How should they change?

### Historical and Philosophical Context

The Dutch Book argument originates with Frank Ramsey and Bruno de Finetti in the early 20th century. An alternative path to the same conclusion is Cox's Theorem, which derives the probability axioms from different desiderata on plausibility reasoning. The convergence of multiple arguments on the same framework is evidence that probability theory is not merely conventional.
