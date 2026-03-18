# Why “Feel” Matters in Data Science

## Introduction: When Instinct Needs Discipline

“Use the Force.”  
“Trust your gut.”  
“Don’t think — just do.”

Cinema loves instinct. It glorifies split-second decisions made on feel alone. In *Top Gun: Maverick*, Pete “Maverick” Mitchell tells his cadets, *“Trust your instincts. Don’t think, just do.”*

<p align="center">
  <img src="Top%20Gun%20Maverick.jpeg" width="600">
</p>

In a fighter jet, that works.

In data science, I’d like to argue the opposite.

Don’t abandon instinct — but don’t let it operate unchecked. Feel matters. Context matters more.

This post explores why developing **data science feel** — a trained sense of plausibility and operational awareness — is essential for producing work that is not only correct, but useful.

---

## The Problem: When Clean Output Lies

As data scientists, we are trained to:

- Fit models  
- Optimize metrics  
- Tune hyperparameters  
- Improve computational efficiency  

But sometimes we forget to ask a more basic question:

**Does this result make sense?**

Perfectly formatted output can still be completely wrong.

And if we don’t pause to evaluate plausibility and possibility, we risk producing conclusions that look sophisticated but fail in reality.

---

## Example 1: The 110% Bone Density Problem

I work as an introductory statistics teaching assistant. Recently, students were given a dataset analyzing bone density loss in nursing mothers. The dataset contained two variables:

- Mother’s age  
- Percentage of bone density lost  

The task was simple: investigate whether bone density loss differed across age groups.

Several students mistakenly used *age* as the response variable instead of bone density loss. They ran regressions, interpreted outputs confidently, and moved on.

One student concluded that a mother lost **110% of her bone density**.

That result isn’t just implausible — it’s impossible.

The issue wasn’t coding.  
It wasn’t algebra.  
It wasn’t statistical technique.

It was context.

They hadn’t stopped to ask:

> Is this physically possible?

This highlights the first filter of good analysis: **plausibility**.

---

## Plausibility vs. Possibility

Though they sound similar, these ideas are distinct:

| Concept       | Question It Asks | Example |
|--------------|------------------|----------|
| Plausibility | Does this make sense given what I know? | 110% bone loss seems unrealistic. |
| Possibility  | Is this even feasible in the real world? | A system cannot lose more than 100% of something. |

Plausibility guards against unlikely conclusions.  
Possibility guards against impossible ones.

Both require feel — not just formulas.

---

## Example 2: Lean Manufacturing and Hidden Constraints

Another example comes from supply chain and [Lean manufacturing](https://www.leanproduction.com/).

<p align="center">
  <img src="Lean%20Manufacturing.png" width="600">
</p>

Lean focuses on maximizing value by eliminating waste — anything that doesn’t add value to the customer. Many of these principles are closely related to quality improvement methodologies such as [Six Sigma](https://www.sixsigmaonline.org/six-sigma-history/), which emphasize reducing variability and improving process control.

In one case study involving car engine filters, analysts suggested removing a touch point on the filter housing. The model suggested it was unnecessary. Removing it would streamline production.

On paper, the recommendation was efficient.

In practice, it was dangerous.

The manufacturing engineer explained that the touch point existed for worker safety. The rest of the component became extremely hot during production. Without the handhold, workers would burn themselves.

The data didn’t show that constraint.  
The model didn’t encode that variable.

Operational reality overruled optimization.

---

## Supply Chain and the “If We Could Have, We Would Have” Principle

Another powerful application of data science in business is supply chain — using data to improve the processes and workflows behind the production and distribution of a product. Professional organizations such as [ASCM (Association for Supply Chain Management)](https://www.ascm.org/) emphasize the importance of integrating analytics with operational context.

<p align="center">
  <img src="SCM%20BlogPost.jpeg" width="600">
</p>

In the industry examples I’ve seen, a quiet theme repeats itself:

> “If we could have, we would have.”

Data scientists are often quick to recommend what the model suggests:

- Reduce inventory  
- Eliminate a buffer  
- Remove a step  
- Shorten lead time  

But rarely is the first solution the full story.

In supply chain especially, it’s critical to approach problems through the lens of Walt Whitman’s advice:

> “Be curious, not judgmental.”

Before assuming inefficiency, we must understand constraints:

- Warehousing capacity  
- Required lead times  
- Production capabilities  
- Safety requirements  
- Regulatory limits  
- Human factors  

Many processes look inefficient because the data doesn’t capture the constraint that necessitates them.

Optimization without context becomes prescription without understanding.

---

## A Practical Framework for Developing Data Science Feel

So how do you apply this?

Before presenting or implementing a result, ask:

1. **What physical or logical limits apply here?**
2. **What would make this result impossible?**
3. **What real-world constraints might not be in my dataset?**
4. **Who operates inside this system daily — and what would they say?**

Good analysts don’t suppress intuition.

They train it.

They develop a feel for:

- Reasonable magnitude ranges  
- Constraint-driven design decisions  
- Tradeoffs between efficiency and resilience  
- When a “clean” solution hides messy consequences  

---

## Conclusion: Data Science Is About Usefulness

Data science can be difficult to define precisely. It spans modeling, engineering, communication, and decision-making.

But one essential component is what a good friend of mine calls **data science feel** — an intuitive awareness of plausibility, feasibility, and operational context.

Without it, we may produce work that resembles data science — work that looks sophisticated and sounds impressive — but ultimately fails to be useful.

And usefulness, at the end of the day, is the true purpose of what we do.

---

## Call to Action

On your next project:

- Write down at least three real-world constraints before modeling.
- Identify one outcome that would be physically impossible.
- Ask someone familiar with the system to sanity-check your assumptions.

Train your feel alongside your technical skills.

Because the most dangerous mistakes in analytics aren’t syntax errors.

They’re results nobody stopped to question.
