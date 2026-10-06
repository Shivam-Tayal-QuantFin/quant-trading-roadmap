# Day 2 — Quant Trading Roadmap 📈

## 📐 Mathematics — Calculus

Studied:

* Derivative rules
* Power Rule
* Product Rule
* Quotient Rule
* Chain Rule
* Applications of derivatives
* Solved **8 calculus problems**

The focus was on building the calculus foundation required for mathematical modelling and quantitative finance.

---

## 🐍 Python — NumPy Fundamentals

Completed **CampusX — Session 13: NumPy Fundamentals** as part of my quantitative Python preparation.

### NumPy Fundamentals

Learned:

* What is NumPy and why it is used for scientific/numerical computing
* NumPy arrays (`ndarray`)
* Creating 1D and multi-dimensional arrays
* Creating arrays using:

  * `np.array()`
  * `np.arange()`
  * `np.linspace()`
  * `np.zeros()`
  * `np.ones()`
  * `np.random`
  * `np.eye()` / `np.identity()`
* Reshaping arrays using `.reshape()`

### Array Attributes

Practiced:

* `.ndim`
* `.shape`
* `.size`
* `.itemsize`
* `.dtype`
* Changing data types using `.astype()`

### Array Operations

Learned:

* Scalar operations
* Vector operations
* Element-wise arithmetic
* Vectorized computation
* Dot product

Example:

```python
import numpy as np

prices = np.array([100, 105, 110, 115])

returns = (prices[1:] - prices[:-1]) / prices[:-1] * 100

print(returns)
```

This is particularly useful for quantitative finance because financial calculations can be performed efficiently across entire arrays of prices or returns.

### NumPy Mathematical & Statistical Functions

Practiced:

* `np.max()`
* `np.min()`
* `np.sum()`
* `np.prod()`
* `np.mean()`
* `np.median()`
* `np.std()`
* `np.var()`
* Trigonometric functions
* `np.log()`
* `np.exp()`
* `np.round()`
* `np.floor()`
* `np.ceil()`

### Array Manipulation

Learned:

* Indexing
* Slicing
* Iterating through arrays
* Reshaping
* Transpose
* `ravel()`
* Vertical stacking — `np.vstack()`
* Horizontal stacking — `np.hstack()`
* Splitting arrays — `np.vsplit()` and `np.hsplit()`

### Quant Finance Connection

NumPy will be an important foundation for:

* Financial return calculations
* Portfolio mathematics
* Statistical analysis
* Monte Carlo simulation
* Vectorized backtesting
* Quantitative models
* Machine learning
* Numerical optimization

---

## 📊 Quant Finance — Futures & Forwards

Studied:

* Definition of futures contracts
* Definition of forward contracts
* Futures vs forwards
* Long and short positions
* Basic payoff intuition
* Profit/loss at maturity
* Hedging and speculation

### Payoff Intuition

**Long Futures/Forward**

If:

`S_T > K`

→ Profit

**Short Futures/Forward**

If:

`S_T < K`

→ Profit

Where:

* `S_T` = underlying price at maturity
* `K` = agreed contract price

The goal was to understand the **payoff structure and economic intuition** before moving toward more mathematical derivative pricing.

---

## 🎯 Day 2 Takeaway

Today I worked on three important foundations for quantitative finance:

**Calculus → Numerical Computing → Financial Derivatives**

I am building these fundamentals step-by-step toward **Quantitative Trading / Quantitative Research**.

### Resources

* CampusX — Data Science Mentorship Program 2022–23
* Session 13: NumPy Fundamentals
* NumPy documentation
* Calculus from Thomas calculus

#QuantFinance #QuantTrading #QuantResearch #Python #NumPy #Calculus #Derivatives #Futures #Forwards #LearningInPublic
