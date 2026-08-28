# Muhammad Afnan

**AI Engineer at Softlixx Technologies.** I use libraries professionally, then rebuild them from scratch to understand why they work.

Day job: RAG systems, LLM pipelines, agentic workflows, production ML.
Free time: open the library, write it from raw math, prove to myself it works.

Not as an exercise. As a standard. Every library I use in production, I've rebuilt at least once.

All of it is public, for the curious people who aren't satisfied with `import`.

---

## 90 Days of ML From Scratch

**[→ The challenge hub](https://github.com/Muh-Afnan/90-days-ml-from-scratch)**

90 projects. Every major concept in modern ML, implemented from raw Python and NumPy. Each repo ships with a derivation, tests, visualizations, and a `learnings.md`.

| Phase | Status |
|---|---|
| Weeks 1–3 · Linear Algebra, Probability & Stats, Calculus & Optimization | ✅ Days 1–15 |
| Weeks 4–5 · Classical ML and Ensembles | ✅ Days 16–25 |
| Week 6 · Neural Networks from Scratch | 🔨 In progress |
| Weeks 7–16 · Deep Learning, Transformers, AI Engineering, Capstones | ⏳ Upcoming |

---

## What I use at work vs. what I've rebuilt

The point of the challenge, in one table.

| I ship with | I've rebuilt | Repo |
|---|---|---|
| `torch.autograd` | Reverse-mode automatic differentiation engine | [autodiff](https://github.com/Muh-Afnan/Automatic-differentiation-engine-from-scratch) |
| `torch.optim.Adam` | SGD, Momentum, Adam with a unified interface | [optimizers](https://github.com/Muh-Afnan/Optimizers-from-Scratch-SGD-Momentum-Adam) |
| `sklearn.decomposition.PCA` | Eigendecomposition-based PCA | [pca](https://github.com/Muh-Afnan/PCA-From-Scratch) |
| `numpy.linalg.svd` | SVD with image compression demo | [svd](https://github.com/Muh-Afnan/Singular-Value-Decomposition) |
| `sklearn.ensemble.RandomForestClassifier` | Bagging + feature importance on my own decision trees | [random-forest](https://github.com/Muh-Afnan/Random-Forest-from-Scratch-Bagging-Feature-Importance-) |
| `xgboost` | Gradient boosting with XGBoost-style second-order splits | [gradient-boosting](https://github.com/Muh-Afnan/Gradient-Boosting-from-Scratch-XGBoost-Concepts-) |
| `sklearn.svm.SVC` | SVM with the kernel trick, visualized | [svm](https://github.com/Muh-Afnan/SVM-from-Scratch-with-Kernel-Trick-Visualized) |
| `sklearn.mixture.GaussianMixture` | GMM fitted with Expectation-Maximization | [gmm-em](https://github.com/Muh-Afnan/Gaussian-Mixture-Models-EM-Algorithm) |
| `scipy.stats.ttest_ind` | Hypothesis testing framework (t-test, chi-square) | [hypothesis-testing](https://github.com/Muh-Afnan/Hypothesis-Testing-Framework) |
| `networkx.pagerank` | PageRank as power iteration on a stochastic matrix | [pagerank](https://github.com/Muh-Afnan/PageRank-Algorithm-Using-Linear-Algebra) |

<details>
<summary><b>All 25 implementations so far, by week</b></summary>

<br>

**Week 1 — Linear Algebra**

| Day | Repo | What it proves |
|---|---|---|
| 1 | [Matrix library](https://github.com/Muh-Afnan/Linear-Algebra-Implementation) | Matrices, vectors, transforms, no NumPy |
| 2 | [Vector transformations](https://github.com/Muh-Afnan/Vector-Transformations) | What eigenvectors do to space, drawn |
| 3 | [PCA](https://github.com/Muh-Afnan/PCA-From-Scratch) | Covariance → eigenvectors → compression |
| 4 | [SVD](https://github.com/Muh-Afnan/Singular-Value-Decomposition) | Matrix factorization + image compression |
| 5 | [PageRank](https://github.com/Muh-Afnan/PageRank-Algorithm-Using-Linear-Algebra) | Google's ranking is an eigenvector problem |

**Week 2 — Probability & Statistics**

| Day | Repo | What it proves |
|---|---|---|
| 6 | [Probability distributions](https://github.com/Muh-Afnan/probability-distribution) | Simulator and visualizer for the core distributions |
| 7 | [Central Limit Theorem](https://github.com/Muh-Afnan/Central-Limit-Theorem---Interactive-Visual-Proof) | Why everything converges to normal, visually |
| 8 | [Bayesian inference engine](https://github.com/Muh-Afnan/Bayesian-Inference-Engine) | Priors, likelihoods, posteriors, updated with evidence |
| 9 | [Hypothesis testing](https://github.com/Muh-Afnan/Hypothesis-Testing-Framework) | t-test and chi-square without scipy |
| 10 | [Monte Carlo](https://github.com/Muh-Afnan/Monte-Carlo-Simulation---Pi-Estimation) | Pi estimation and finance sims |

**Week 3 — Calculus & Optimization**

| Day | Repo | What it proves |
|---|---|---|
| 11 | [Gradient descent visualizer](https://github.com/Muh-Afnan/Gradient-Descent-Visualizer) | Optimization on 1D curves, contours, 3D surfaces |
| 12 | [Autodiff engine](https://github.com/Muh-Afnan/Automatic-differentiation-engine-from-scratch) | The core of how PyTorch computes gradients |
| 13 | [Optimizers](https://github.com/Muh-Afnan/Optimizers-from-Scratch-SGD-Momentum-Adam) | SGD, Momentum, Adam compared head to head |
| 14 | [Loss landscape explorer](https://github.com/Muh-Afnan/Convexity-Loss-Landscape-Explorer) | Convexity and the geometry of convergence |
| 15 | [Newton vs gradient descent](https://github.com/Muh-Afnan/Newton-s-Method-vs-Gradient-Descent) | When curvature is worth the compute |

**Week 4 — Classical ML**

| Day | Repo | What it proves |
|---|---|---|
| 16 | [Linear regression](https://github.com/Muh-Afnan/Linear-Regression-from-Scratch) | Closed form and gradient descent, full derivation |
| 17 | [Logistic regression](https://github.com/Muh-Afnan/Logistic-Regression-Decision-Boundary-Visualizer) | Sigmoid, cross-entropy, decision boundaries drawn |
| 18 | [Decision tree](https://github.com/Muh-Afnan/Decision-Tree-from-Scratch-ID3-Gini-) | ID3 and Gini splits, recursive tree building |
| 19 | [K-Means](https://github.com/Muh-Afnan/K-Means-Clustering-from-Scratch-Convergence-Visualizer) | Lloyd's algorithm with convergence animation |
| 20 | [Naive Bayes](https://github.com/Muh-Afnan/Naive-Bayes-Classifier-from-Scratch-on-Text-Data) | Text classification from counts and priors |

**Week 5 — Advanced Classical ML**

| Day | Repo | What it proves |
|---|---|---|
| 21 | [Random Forest](https://github.com/Muh-Afnan/Random-Forest-from-Scratch-Bagging-Feature-Importance-) | Bagging, OOB, feature importance |
| 22 | [SVM](https://github.com/Muh-Afnan/SVM-from-Scratch-with-Kernel-Trick-Visualized) | Margins and the kernel trick, visualized |
| 23 | [Gradient boosting](https://github.com/Muh-Afnan/Gradient-Boosting-from-Scratch-XGBoost-Concepts-) | Boosting internals, XGBoost concepts |
| 24 | [KNN + KD-tree](https://github.com/Muh-Afnan/KNN-from-Scratch-KD-Tree-Optimization) | Distance search, then making it fast |
| 25 | [GMM + EM](https://github.com/Muh-Afnan/Gaussian-Mixture-Models-EM-Algorithm) | Soft clustering with Expectation-Maximization |

</details>

---

## Professionally

```python
work = {
    "LLM applications": ["RAG systems", "retrieval pipelines", "context management"],
    "AI agents":        ["tool use", "orchestration", "multi-agent workflows"],
    "Applied NLP":      ["embeddings", "fine-tuning", "generative AI"],
    "Production ML":    ["end-to-end pipelines", "deployment", "monitoring"],
}
```

Python · PyTorch · NumPy · LangChain · scikit-learn · FastAPI · Docker · Git

---

<details>
<summary><b>Why a designer ended up here</b></summary>

<br>

Four years in design at Softlixx, the last of them as Senior Graphic Designer, before moving into AI engineering full time.

The design background is the lens, not the limitation.

| Design | ML equivalent |
|---|---|
| Client revision cycles | Gradient descent |
| A logo built for one client | Overfitting |
| Design systems and components | Network layers |
| Client feedback loops | Backpropagation |
| Creative brief constraints | Regularization |

Years inside feedback loops and constraint-based systems make the math of ML click differently.

</details>

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-afnan-3272a2218)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/m.r_afnan)

*For the curious people. Always open.*

</div>
