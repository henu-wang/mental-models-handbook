# Mental Models Handbook

A structured reference of **25+ mental models** drawn from physics, economics, psychology, biology, and mathematics. Mental models are the thinking tools that help you understand how the world works, make better predictions, and avoid costly mistakes.

## Table of Contents

- [What Are Mental Models?](#what-are-mental-models)
- [Physics & Engineering](#physics--engineering)
  - [1. First Principles Thinking](#1-first-principles-thinking)
  - [2. Entropy (Second Law of Thermodynamics)](#2-entropy-second-law-of-thermodynamics)
  - [3. Critical Mass / Tipping Points](#3-critical-mass--tipping-points)
  - [4. Leverage](#4-leverage)
  - [5. Feedback Loops](#5-feedback-loops)
- [Economics & Business](#economics--business)
  - [6. Opportunity Cost](#6-opportunity-cost)
  - [7. Incentives](#7-incentives)
  - [8. Supply and Demand](#8-supply-and-demand)
  - [9. Comparative Advantage](#9-comparative-advantage)
  - [10. Network Effects](#10-network-effects)
  - [11. Economies of Scale](#11-economies-of-scale)
- [Psychology & Human Behavior](#psychology--human-behavior)
  - [12. Confirmation Bias](#12-confirmation-bias)
  - [13. Dunning-Kruger Effect](#13-dunning-kruger-effect)
  - [14. Loss Aversion](#14-loss-aversion)
  - [15. Anchoring](#15-anchoring)
  - [16. Social Proof](#16-social-proof)
  - [17. Sunk Cost Fallacy](#17-sunk-cost-fallacy)
  - [18. Availability Heuristic](#18-availability-heuristic)
- [Biology & Evolution](#biology--evolution)
  - [19. Natural Selection / Evolution](#19-natural-selection--evolution)
  - [20. Red Queen Effect](#20-red-queen-effect)
  - [21. Adaptation](#21-adaptation)
  - [22. Ecosystems & Niches](#22-ecosystems--niches)
- [Mathematics & Systems](#mathematics--systems)
  - [23. Power Laws (Pareto)](#23-power-laws-pareto)
  - [24. Compounding](#24-compounding)
  - [25. Bayes' Theorem](#25-bayes-theorem)
  - [26. Margin of Safety](#26-margin-of-safety)
- [How to Build a Latticework of Models](#how-to-build-a-latticework-of-models)
- [Resources](#resources)
- [License](#license)

---

## What Are Mental Models?

Charlie Munger describes mental models as "the big ideas from the big disciplines." Rather than seeing the world through one lens, you develop a **latticework of models** — a multidisciplinary toolkit that gives you a more accurate, nuanced understanding of reality.

> "You've got to have models in your head. And you've got to array your experience — both vicarious and direct — on this latticework of models." — Charlie Munger

**Why collect mental models?**
- The person with one model tries to fit all problems to it ("To a man with a hammer, everything looks like a nail")
- Multiple models let you triangulate: approach a problem from physics, then economics, then psychology
- Better models → better predictions → better decisions

---

## Physics & Engineering

### 1. First Principles Thinking

**Discipline:** Physics (Aristotle, popularized by Elon Musk)

**Definition:** Break a problem down to its most fundamental truths and reason up from there, rather than reasoning by analogy.

**Process:**
```
1. Identify your assumption
2. Break it down to fundamental truths
3. Create new solutions from the ground up
```

**Example:**
- Analogy reasoning: "Batteries cost $600/kWh, they always have, so electric cars will always be expensive."
- First principles: "Batteries are made of cobalt, nickel, aluminum, carbon, and polymers. What do these materials cost on the commodity market? About $80/kWh. So the cost problem is manufacturing, not materials."

**Application:** Product design, cost reduction, innovation, challenging "we've always done it this way."

---

### 2. Entropy (Second Law of Thermodynamics)

**Discipline:** Physics

**Definition:** In any closed system, disorder (entropy) tends to increase over time. Things fall apart naturally; maintaining order requires continuous energy input.

**Business implication:**
- Codebases decay without refactoring
- Relationships weaken without investment
- Companies become bureaucratic without deliberate effort
- Skills atrophy without practice

**Key takeaway:** Maintenance isn't optional — it's physics. Budget energy for upkeep, not just creation.

---

### 3. Critical Mass / Tipping Points

**Discipline:** Nuclear physics → Social dynamics

**Definition:** The minimum amount of resources/activity needed to sustain a chain reaction. Below critical mass, the reaction fizzles. Above it, it becomes self-sustaining.

**Applications:**
- Startups need enough users for network effects to kick in
- Social movements need enough participants to become self-sustaining
- Products need enough features to be viable but not so many they're bloated

---

### 4. Leverage

**Discipline:** Physics (Archimedes)

**Definition:** A small input force amplified by a lever to produce a larger output force.

> "Give me a lever long enough and a fulcrum on which to place it, and I shall move the world." — Archimedes

**Forms of leverage in business:**

| Type | Examples | Characteristics |
|------|----------|----------------|
| **Labor** | Employees, contractors | Linear scaling, management overhead |
| **Capital** | Investment, loans | Amplifies returns (and losses) |
| **Code** | Software, automation | Zero marginal cost replication |
| **Media** | Content, audience | Compounds over time |

---

### 5. Feedback Loops

**Discipline:** Systems engineering

**Types:**

| Type | Mechanism | Example |
|------|-----------|---------|
| **Positive (reinforcing)** | Output amplifies input | Compound interest, viral growth, bank runs |
| **Negative (balancing)** | Output dampens input | Thermostat, market corrections, immune response |

**Key insight:** Identify whether you're in a reinforcing loop (where small actions compound) or a balancing loop (where the system resists change). Design systems with appropriate feedback.

---

## Economics & Business

### 6. Opportunity Cost

**Definition:** The value of the next-best alternative you give up when making a choice. Every decision has a cost — even "free" things cost time.

**Formula:**
```
Opportunity Cost = Value of Best Forgone Alternative
```

**Example:** Attending a 2-hour meeting doesn't just cost 2 hours. It costs whatever else you could have accomplished in those 2 hours — code shipped, customers called, strategy refined.

**Application:** Time management, investment decisions, hiring priorities.

---

### 7. Incentives

**Definition:** People respond to incentives — rewards and punishments shape behavior more reliably than appeals to logic or morality.

> "Show me the incentive and I will show you the outcome." — Charlie Munger

**Categories:**

| Type | Example |
|------|---------|
| **Financial** | Bonuses, commissions, fines |
| **Social** | Status, recognition, peer pressure |
| **Moral** | Guilt, duty, purpose |

**Key insight:** When a system produces bad outcomes, look at the incentives before blaming the people. Misaligned incentives produce predictable misbehavior.

---

### 8. Supply and Demand

**Definition:** Prices are determined by the intersection of supply (what sellers offer) and demand (what buyers want). Scarcity increases value; abundance decreases it.

**Career application:** Your salary is a function of supply (how many people can do your job) and demand (how many companies need it done). To increase your value: decrease the supply side (develop rare skills) or increase the demand side (enter growing fields).

---

### 9. Comparative Advantage

**Definition:** Even if you're better at everything than someone else, you both benefit by specializing in what you're *relatively* best at.

**Example:** A lawyer who types 80 WPM and their assistant who types 60 WPM. The lawyer is faster at typing, but their time is worth more doing legal work. Both benefit when the lawyer focuses on law and the assistant handles typing.

---

### 10. Network Effects

**Definition:** A product becomes more valuable as more people use it.

**Types:**
- **Direct:** Each user increases value for all users (telephone, social media)
- **Indirect:** More users attract more complementary products (iOS users attract app developers attract more iOS users)
- **Data:** More users generate more data, which improves the product (Google Search, recommendation algorithms)

---

### 11. Economies of Scale

**Definition:** Cost per unit decreases as production volume increases.

**Sources:** Bulk purchasing, spreading fixed costs, specialization, learning curves.

**Counterpoint — Diseconomies of scale:** Beyond a certain size, organizations become slower, more bureaucratic, and less innovative. There's often an optimal size.

---

## Psychology & Human Behavior

### 12. Confirmation Bias

**Definition:** The tendency to search for, interpret, and remember information that confirms your pre-existing beliefs.

**How to counteract:**
- Actively seek disconfirming evidence
- Ask: "What would change my mind?"
- Assign a "devil's advocate" in group decisions
- Read sources you disagree with

---

### 13. Dunning-Kruger Effect

**Definition:** People with low ability at a task overestimate their ability; people with high ability underestimate theirs.

```
Confidence
    ^
    |  *          Beginners peak
    |   \
    |    \        Valley of despair
    |     \___
    |         \___________/*  Experts
    |
    └──────────────────────→ Experience
```

**Application:** Be most skeptical of your opinions in areas where you've just started learning.

---

### 14. Loss Aversion

**Definition:** The pain of losing is psychologically about twice as powerful as the pleasure of gaining. A $100 loss feels worse than a $100 gain feels good.

**Implications:**
- People hold losing investments too long (hoping to avoid realizing the loss)
- Framing matters: "save $50" is more motivating than "gain $50"
- Subscription models work because canceling feels like a loss

---

### 15. Anchoring

**Definition:** Over-reliance on the first piece of information encountered when making decisions.

**Example:** A shirt listed at $100 marked down to $60 feels like a deal. But is the shirt worth $60 on its merits? The $100 anchor distorts your evaluation.

**Defense:** Always evaluate options independently before looking at reference points, competitor prices, or historical data.

---

### 16. Social Proof

**Definition:** People copy the behavior of others, especially in uncertain situations. "If everyone else is doing it, it must be right."

**Uses and abuses:**
- Positive: Customer testimonials, user counts, "bestseller" badges
- Negative: Herd behavior, groupthink, speculative bubbles

---

### 17. Sunk Cost Fallacy

**Definition:** Continuing an endeavor because of previously invested resources (time, money, effort) that cannot be recovered.

**Test:** "If I were starting from scratch today, would I start this project/relationship/investment?" If no, the sunk costs are trapping you.

---

### 18. Availability Heuristic

**Definition:** Overweighting information that comes to mind easily (recent, vivid, emotionally charged) when estimating probability.

**Example:** After seeing news coverage of a plane crash, people overestimate the danger of flying relative to driving, even though driving is statistically far more dangerous.

---

## Biology & Evolution

### 19. Natural Selection / Evolution

**Definition:** Organisms with traits better suited to their environment survive and reproduce more. Over time, these advantageous traits become more common.

**Business parallel:** Markets are evolutionary systems. Companies that adapt to changing environments survive. Those that don't, die. Innovation is mutation; the market is selection pressure.

---

### 20. Red Queen Effect

**Definition:** "It takes all the running you can do, to keep in the same place." — Lewis Carroll

In competitive environments, you must continuously improve just to maintain your position, because your competitors are also improving.

**Application:** Product development, career skills, security (attacker/defender arms race).

---

### 21. Adaptation

**Definition:** Organisms adjust to their environment over time. Resistance to change is natural but can be fatal when the environment shifts.

**Key insight:** What made you successful in one environment may not work in another. Adaptability > strength.

---

### 22. Ecosystems & Niches

**Definition:** Every organism occupies a specific niche in an ecosystem. Competition is fiercest between similar species. Differentiation is survival.

**Business application:** Don't compete directly with giants. Find or create a niche where your unique combination of strengths gives you an advantage.

---

## Mathematics & Systems

### 23. Power Laws (Pareto)

**Definition:** In many systems, a small number of inputs produce a disproportionate share of outputs.

- 20% of customers generate 80% of revenue
- 20% of bugs cause 80% of crashes
- 20% of features get 80% of usage

**Application:** Identify the vital few and focus ruthlessly.

---

### 24. Compounding

**Definition:** Growth on growth. Returns build on previous returns, creating exponential rather than linear growth.

```
Linear:     1, 2, 3, 4, 5, 6, 7, 8, 9, 10
Compounding: 1, 2, 4, 8, 16, 32, 64, 128, 256, 512
```

**Applies to:** Investment returns, knowledge, skills, relationships, habits, reputation.

> "Compound interest is the eighth wonder of the world." — (attributed to Einstein)

**Key insight:** The most important variable in compounding is **time**. Starting early dominates starting with more.

---

### 25. Bayes' Theorem

**Definition:** Update your beliefs based on new evidence. The probability of a hypothesis depends on both the prior probability and the likelihood of the observed evidence.

```
P(H|E) = P(E|H) × P(H) / P(E)
```

**In plain English:** When you receive new information, adjust your confidence in your beliefs proportionally. Strong prior evidence requires strong new evidence to overturn.

**Application:** Medical diagnosis, spam filtering, any situation where you're updating beliefs as new data arrives.

---

### 26. Margin of Safety

**Definition:** Build in a buffer between what you expect and what you plan for. Engineers don't design bridges to handle *exactly* the expected load — they design for 2-3x the expected load.

**Applications:**
- Investing: Buy stocks significantly below estimated intrinsic value
- Project management: Add buffer time to estimates
- Engineering: Design systems to handle 2-3x expected load
- Personal finance: Emergency fund = margin of safety for income

---

## How to Build a Latticework of Models

1. **Read widely across disciplines** — Don't just read within your field
2. **Practice application** — When you encounter a situation, ask "Which models apply here?"
3. **Keep a decision journal** — Record your reasoning and which models you used
4. **Combine models** — The best insights come from applying multiple models to one problem
5. **Teach others** — Explaining a model reveals gaps in your understanding
6. **Revisit and refine** — Models that served you well in one context may mislead in another

For a curated collection of investing principles and mental models applied to real decisions, visit [KeepRule](https://keeprule.com/en/principles) — an interactive platform for mastering the mental models of history's greatest thinkers.

---

## Resources

**Essential Reading:**
- *Poor Charlie's Almanack* — Charlie Munger
- *The Great Mental Models* (Vol. 1-4) — Shane Parrish
- *Thinking, Fast and Slow* — Daniel Kahneman
- *Seeking Wisdom* — Peter Bevelin
- *The Art of Thinking Clearly* — Rolf Dobelli

---

## Contributing

Found a model that should be included? Open an issue or submit a PR. Please follow the existing format:
- Model name and origin
- Clear definition
- Practical examples
- When to apply it

---

## License

MIT License — see [LICENSE](LICENSE) for details.
