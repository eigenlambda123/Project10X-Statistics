# **Distribution Explorer**

An interactive Python-based simulation tool to explore **discrete probability distributions** — Binomial, Geometric, and Poisson — using randomized sampling, PMF overlays, and statistical analysis.

---

## **Features**

### Simulate Discrete Distributions:

- **Binomial Distribution**
    - Simulates number of successes in nn trials.

- **Geometric Distribution**
    - Simulates number of trials until the first success.

- **Poisson Distribution**
    - Simulates number of events in a time interval with average rate λ\lambda.


### Visualize Simulations vs Theory:

- Histograms of simulation outcomes.
- Overlay **theoretical PMF** curves from `scipy.stats`.
- Supports varying sample sizes: 100, 1,000, 10,000+

### Analyze Statistical Properties:

- Compare **empirical** mean and variance with **theoretical** values.
- Shape insight (symmetric, right-skewed, left-skewed).
- Verify Law of Large Numbers visually and numerically.

### Interactive CLI Interface:

- Choose distribution and input parameters:
    - Number of trials, probability, rate $\lambda$, etc.

- Menu-driven workflow:
    - Simulate only, visualize, or run full analysis.

---

## **Usage**

1. **Run the script:**

    ```bash
    python distribution_explorer.py
    ```

2. **Choose an option from the menu:**

    ```
    Discrete Distribution Simulator
    1. Binomial Distribution
    2. Geometric Distribution
    3. Poisson Distribution
    4. Visualize and Compare (Simulated vs Theoretical) + Analysis
    ```

3. **Provide input values** as prompted:
    - Number of simulations
    - Desired number of successes/events
    - Probability $p$ or rate $\lambda$

4. **View Output:**
    - Simulation results
    - Histogram with overlaid PMF
    - Empirical vs theoretical stats comparison

---

## **Installation**

Requires Python 3.x. Install dependencies:

```bash
pip install numpy scipy matplotlib
```

---

## **Notes**

- All randomness uses `numpy.random`.
- PMF overlays use `scipy.stats`:
    - `binom.pmf`, `geom.pmf`, `poisson.pmf`
- GUI required for plot visualization (Jupyter, VSCode, etc.)
- Simulation results vary slightly across runs (random sampling).
