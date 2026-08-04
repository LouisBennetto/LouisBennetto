# Louis Bennetto

**Incoming MSc Mathematics and Finance, Imperial College London** (September 2026)
**BSc Mathematics, Durham University** (First-Class Honours)

Stochastic modelling and numerical methods, with a focus on derivative pricing,
market microstructure and reinforcement learning. Currently seeking quantitative
researcher roles.

---

## Projects

### [Barrier-Option-MC-Pricer](https://github.com/LouisBennetto/Barrier-Option-MC-Pricer)

Prices a down-and-out barrier option by five independent routes and reconciles them.

- **13.9x** variance reduction from combining antithetic variates with importance
  sampling, well above the 4.6x implied by treating the two as independent
- Crank-Nicolson PDE solver and the Rubinstein-Reiner closed form agree to
  **1.2e-4** relative, from entirely unrelated error sources
- Monte Carlo and the Broadie-Glasserman-Kou discrete-monitoring correction agree
  to within **1.06 standard errors**
- Shows antithetic variance reduction *decays* as the barrier approaches spot,
  from 2.00x to 1.08x, which is the opposite of the usual intuition

### [Avellaneda-Stoikov-Market-Maker](https://github.com/LouisBennetto/Avellaneda-Stoikov-Market-Maker)

Optimal market making under inventory risk, and the mechanism that actually controls it.

- Inventory standard deviation cut **78%** by quote *skew* rather than spread width,
  confirmed by a mean-reversion slope strengthening from -0.0005 to -0.21
- Exact three-term PnL decomposition holding to **3e-15** relative, replacing a
  widely quoted approximation that is not an identity
- Documents a fill-convention defect that silently removes inventory mean reversion
  while leaving every headline figure plausible, with regression tests that catch it

### [Reward-Function-Design-in-Discrete-Domain-Reinforcement-Learning](https://github.com/LouisBennetto/Reward-Function-Design-in-Discrete-Domain-Reinforcement-Learning)

BSc dissertation comparing seven reward-design methods in a discrete stochastic game.

- Inverse RL lifted Monte Carlo control to **44.2%** against a **33.2%** sparse baseline
- Potential-based shaping lifted Q-learning to **47.6%** against **40.7%**
- Every method benchmarked against optimal policies computed by value iteration,
  rather than against each other

---

## In progress

- **Reward design under risk aversion.** Extends the dissertation into the
  market-making model above, using an exact backward induction as the benchmark.
- **EEG entropy-complexity and integrated information modelling.** Private pending
  publication of the associated paper.

---

## Contact

[LinkedIn](https://linkedin.com/in/louis-bennetto)
