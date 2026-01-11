## Chapter 6: Priors

Bayes' theorem tells me how to get from prior to posterior. It does not tell me where priors come from.

If I start with different priors, I end with different posteriors. Two people with the same evidence but different starting beliefs will reach different conclusions. So isn't this all just subjective?

This is a genuine problem, and I will not pretend to have a complete solution. But the situation is not as bad as it might seem.

Even if priors are somewhat arbitrary, the **update rule is not**. Two people with different priors who see the same evidence will update in the same direction. Over time, with enough shared evidence, their beliefs will **converge**. Bad priors get washed out by data. The process is self-correcting—not immediately, but eventually.

Moreover, not all priors are equally defensible. A prior that assigns zero probability to a possibility that is not logically ruled out is pathological: Bayes' theorem will never update away from zero, no matter the evidence. Such priors are closed to learning. Among priors that remain open to evidence, some encode unjustified confidence while others encode appropriate humility. The choice is not arbitrary even if it is not unique.

There are also principled methods for choosing priors in cases of ignorance. Maximum entropy priors, for example, spread probability as evenly as possible given known constraints—they do not pretend to knowledge I lack. Symmetry principles sometimes motivate specific choices. These methods do not solve all cases, but they provide guidance.

In practice, I am rarely in a state of complete ignorance. I have background knowledge, previous experience, evidence from related domains. My priors are informed by everything I have already learned.

But I am honest: the problem of priors is not fully solved. This is genuine uncertainty of a kind different from uncertainty about the world. I do not know the "correct" prior for many questions. I make my best guess, update on evidence, and remain open to revision.

What I have certainty about is the update rule. However I start, I know how to learn. I now have beliefs about the world. But I also need to act. How should I choose?

### Historical and Philosophical Context

The problem of priors is one of the deepest issues in Bayesian epistemology. "Objective Bayesians" like E.T. Jaynes sought principled methods for prior selection (maximum entropy, transformation groups). "Subjective Bayesians" like de Finetti accepted that priors are personal, arguing that the objectivity comes from the update rule and eventual convergence. The debate continues.
