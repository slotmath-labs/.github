# SlotMath Labs (Applied Probability Institute)

[![Research Portal](https://img.shields.io/badge/Portal-slotmath.org-00E5FF.svg)](https://slotmath.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Open Science: Datasets](https://img.shields.io/badge/Data-Open%20Access-purple.svg)](https://slotmath.org/en/research/)
[![Affiliation](https://img.shields.io/badge/Institution-Applied%20Probability%20Institute-gold.svg)](https://slotmath.org/en/about/)

**SlotMath Labs** is an independent quantitative research collective operating under the **Applied Probability Institute**. We engineer deterministic combinatorial models, open-access stochastic simulation engines, and discrete probability benchmarks for modern slot architectures, configurable RTP profiles, and virtual reel mechanics.

---

## 🔬 Core Open-Source Repositories

| Repository | Focus & Domain | Language / Stack | License |
| :--- | :--- | :--- | :--- |
| **[`slot-rtp-monte-carlo-simulator`](https://github.com/slotmath-labs/slot-rtp-monte-carlo-simulator)** | High-throughput Monte Carlo simulation engine (up to 100M spins), Central Limit Theorem convergence, and standard error decay | TypeScript / Python | MIT |
| **[`slot-volatility-index-calculator`](https://github.com/slotmath-labs/slot-volatility-index-calculator)** | Volatility Index ($VI_{95}$), standard deviation boundaries, multi-trajectory Markov models, and absorption ruin metrics | TypeScript / ESM | MIT |
| **[`bonus-buy-ev-evaluator`](https://github.com/slotmath-labs/bonus-buy-ev-evaluator)** | Mathematical expectation evaluator, Pareto right-skewed payout modeling, dud frequency analysis ($<20\times$), and tail risk | TypeScript / ESM | MIT |
| **[`research-papers`](https://github.com/slotmath-labs/research-papers)** | Preprints, 100M-spin empirical convergence datasets, commercial operator RTP audit matrices, and verification suites | Markdown / CSV / Python | CC-BY-4.0 |

---

## 📊 Research Pillars

1. **RTP Mechanics & Virtual Reel Strip Invariants**: Discrete probability mass functions across virtual strips ($L_1 \times L_2 \times \dots \times L_k$), theoretical vs actual RTP convergence, and turnover velocity capital depletion models.
2. **Volatility Indices & Dispersion Dynamics**: Statistical modeling of slot variance, 90%/95%/99% confidence intervals, standard deviation contraction ($\sigma / \sqrt{N}$), and Gambler's Fallacy refutations.
3. **Feature Buy Economics & Fat-Tail Distortion**: Closed-form mathematical derivations of Bonus Buy expected value, variance multiplier acceleration, and absorption barrier ruin probability.
4. **Bankroll Algorithms & Regulatory Standards**: Markov chain ruin models, Doob's Optional Stopping Theorem proofs on negative expectation invariance, and GLI-19/BMM Dieharder CSPRNG certification standards.

---

## 🌐 Publications & Live Interactive Calculators

All research papers, interactive zero-runtime client-side calculators, and quantitative glossaries are accessible open-access at **[slotmath.org](https://slotmath.org)**:
- **RTP & Confidence Interval Inspector**: [slotmath.org/tools/rtp-inspector/](https://slotmath.org/en/tools/rtp-inspector/)
- **Slot Volatility & Drawdown Simulator**: [slotmath.org/tools/volatility-simulator/](https://slotmath.org/en/tools/volatility-simulator/)
- **Bonus Buy EV & Variance Distortion Analyzer**: [slotmath.org/tools/bonus-buy-analyzer/](https://slotmath.org/en/tools/bonus-buy-analyzer/)
- **Bankroll Decay & Spin Survival Calculator**: [slotmath.org/tools/bankroll-decay/](https://slotmath.org/en/tools/bankroll-decay/)
- **Commercial Operator RTP Audit**: [slotmath.org/benchmarks/operator-rtp-audit/](https://slotmath.org/en/benchmarks/operator-rtp-audit/)

---

### Academic Citation

If you utilize our algorithms, simulation suites, or datasets in your academic research or applications, please cite:

```bibtex
@article{slotmath2026empirical,
  title={Empirical Distribution of Slot RTP, Volatility Indices, and Tail Win Probabilities Across 100 Million Simulated Spins},
  author={{SlotMath Labs} and {Applied Probability Institute}},
  journal={Applied Probability Institute Research Hub},
  year={2026},
  url={https://slotmath.org/en/research/slot-volatility-100m-simulation-study/}
}
```
