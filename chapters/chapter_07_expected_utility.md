# Part IV: Choice Under Uncertainty

## Chapter 7: Expected Utility

I have probabilistic beliefs about an uncertain world. I have goals I want to achieve. I need to choose actions.

How should I choose?

This is not a question about how I *do* choose—that is psychology. It is a question about what choice procedure avoids self-defeat. Just as I wanted my beliefs to be coherent (not exploitable via Dutch Books), I want my choices to be coherent (not exploitable via trades that leave me worse off).

The question, then, is what structure my preferences must have to avoid such exploitation.

Consider **transitivity**: if I prefer $A$ to $B$ and $B$ to $C$, I should prefer $A$ to $C$. If I violate this—preferring $A$ to $B$, $B$ to $C$, and $C$ to $A$—I become a money pump. You can charge me to trade $C$ for $B$, then $B$ for $A$, then $A$ for $C$, and I end up where I started but poorer. I accept each trade (I prefer what I'm getting), but the sequence exploits me. So I commit to transitivity.

Consider **completeness**: for any two outcomes, I either prefer one, prefer the other, or am indifferent. This is less obviously required. Perhaps I simply cannot compare some outcomes. But if I cannot compare, I cannot choose coherently between them when choice is forced. I may not be exploitable, but I am paralyzed. Since I must act, I commit to having preferences that are complete enough for the choices I face.

Consider **continuity**: if I prefer $A$ to $B$ to $C$, there is some probability mix of $A$ and $C$ that I find equally good as $B$. This rules out "lexicographic" preferences where one consideration absolutely trumps another regardless of probabilities. Such preferences might not make me a money pump, but they prevent any tradeoffs whatsoever. I find this implausible for my actual preferences—I do make tradeoffs—so I accept continuity.

Consider **independence**: if I prefer $A$ to $B$, I should prefer a lottery involving $A$ to the same lottery with $B$ substituted. Adding the same irrelevant possibility to both options should not reverse my preference. This axiom is the most contested. Some argue it is too strong. I accept it because violating it leads to preferences that change based on options I will never face, which seems like a failure of coherence.

These are **commitments**, not proofs. I accept these axioms because violating them either makes me exploitable or leads to choice behavior I find incoherent. Others might draw the line differently.

Given these axioms, a mathematical result follows: the **von Neumann-Morgenstern theorem** states that my preferences can be represented by a utility function $U$, and I prefer $A$ to $B$ if and only if the expected utility of $A$ exceeds that of $B$. The proof appears in the appendix.

This is not advice that I *should* maximize expected utility. It is a theorem that if my preferences satisfy the axioms, they *already constitute* expected utility maximization. The procedure is implicit in the preferences.

What does this mean in practice, and what does utility actually represent?

### Historical and Philosophical Context

The expected utility framework originates with Daniel Bernoulli's 1738 resolution of the St. Petersburg paradox, but the modern axiomatic treatment is due to John von Neumann and Oskar Morgenstern in *Theory of Games and Economic Behavior* (1944). Leonard Savage extended this in *The Foundations of Statistics* (1954), deriving both probability and utility from preferences over acts.
