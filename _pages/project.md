---
layout: single
title: "Project"
permalink: /project/
author_profile: false
---

This page presents the motivation, background, and objectives of my MathQuantum High School Fellowship project.

---

## Project Idea

This project develops a quantum-inspired optimization model for decision-making under uncertainty, motivated by Venezuelan micro-enterprises. The crux of the research is a stylized, parameterized problem in which a firm chooses production and/or investment levels given uncertain future demand and prices. The decision space is encoded into a small quantum circuit (using qubits, superposition, and a variational/QAOA-style ansatz), and measurement outcomes are interpreted as candidate decisions. Linear algebra and probability are used to define an objective (e.g., expected profit with a risk penalty) and to analyze the resulting decision distributions. A Python/GitHub implementation will compare this quantum-inspired approach against classical baselines on synthetic scenarios, providing a computational foundation that can later be extended with real or more realistic data.

---

## Background

The MathQuantum Research Training Group's High School Fellowship introduces core quantum information concepts such as qubits, gates, superposition, entanglement, and simple quantum-inspired algorithms (variational circuits, QAOA-style ansatz) that can encode small optimization problems. These tools provide a natural language for representing uncertainty and discrete decision spaces in a compact, mathematically precise way.

Venezuelan micro-enterprises (e.g., small shops, artisanal workshops, food stands) operate under high uncertainty in prices, demand, and supply conditions due to drastic political and economic circumstances. Rather than modeling specific real firms, this project defines a stylized decision problem that captures key features of such environments:

- Discrete or discretized decision variables (e.g., production quantity, inventory level, investment choice).
- Stochastic demand and/or price modeled via simple probability distributions (e.g., normal, lognormal, or scenario-based).
- An objective function combining expected profit and a simple risk measure (e.g., variance, downside risk, or Conditional Value-at-Risk).

Recent work in quantum computing and quantum-inspired optimization has explored applications in finance, operations research, and decision-making under uncertainty; this shows how quantum algorithms can represent and sample from complex probability distributions and optimization landscapes. This project combines these aforementioned ideas with the local Venezuelan context, eventually resulting in a formal, computational model that will:

- Be fully specified mathematically.
- Be implemented in Python with reproducible simulations.
- Compare quantum-inspired and classical strategies on synthetic scenarios.
- Be designed so that more realistic or empirical data can be incorporated in future work.

---

## Motivation

### Scientific Motivation

To formulate and analyze a well-posed, quantum-inspired optimization model for decision-making under uncertainty, using tools learned from MathQuantum (basic circuits, measurements, linear algebra, probability) and connecting them to economic concepts such as risk and resilience.

### Personal / Venezuelan Roots

To connect an engineering mindset and Venezuelan background to Quantum Information Science (QIS) by grounding the model in challenges faced by local micro-enterprises, while maintaining mathematical rigor and avoiding over-claiming.

### Educational Motivation

To create a clear, reproducible computational framework (Python/GitHub) that demonstrates how quantum concepts learned in MathQuantum can be assembled into a research-style prototype, with a clear path to extension and possible publication.

---

## Complementary Video

**Optimization Problem on Quantum Computers – Lecture 1**

Yassine Hamoudi, *Optimization problem on quantum computers – Lecture 1*, CEMRACS Quantum Computing Summer School, CIRM (2025).

<https://www.youtube.com/watch?v=Y1aMUhRfzLU>

This lecture provides an accessible introduction to quantum optimization and variational algorithms, including many of the concepts that motivate this project, such as parameterized quantum circuits, optimization landscapes, and quantum approaches to solving discrete optimization problems.

---
## Goals

### Quantum Information / Physics

Apply core MQ concepts (qubits, gates, measurements, simple variational/QAOA-style algorithms) in a concrete, well-specified optimization problem.

### Mathematics & Statistics

Use linear algebra and probability to define the decision space, uncertainty model, objective function, and risk metrics; analyze circuit outputs and measurement statistics.

### Economics

Frame decisions in terms of profit and risk under uncertainty with a clear mathematical objective, without deep econometrics or claims about real policy.

### Engineering

Implement the full model in Python/GitHub, including quantum-inspired and classical baselines, synthetic scenario generation, and performance comparison; consider scalability, noise, and implementation constraints.

### Venezuelan Roots

Keep cultural and personal context central to the narrative motivation.

---

## Post-MathQuantum Vision

After MathQuantum, this project will be extended into a fully specified computational study. The decision problem will be formalized mathematically, with clearly defined variables, constraints, uncertainty models, objective functions, and risk measures. The quantum-inspired ansatz and the classical baseline optimizer will be specified in detail, and the full pipeline will be implemented in Python/GitHub, including synthetic scenario generation, quantum-inspired and classical optimizers, and performance metrics such as expected profit, risk measures, and decision distributions. Systematic comparisons will be carried out across scenarios to study how circuit depth, entanglement structure, and noise affect performance, and to explore how more realistic or empirical data could be incorporated in future work. The final output will be written up as a short report or preprint targeting venues in quantum information, quantum-inspired optimization, or applied quantum computing, with the long-term goal of journal-quality research in quantum science and engineering.

---

## References

1. Nielsen, M. A., & Chuang, I. L. *Quantum Computation and Quantum Information* (10th Anniversary ed.). Cambridge University Press, 2010.

2. Preskill, J. "Quantum Computing in the NISQ Era and Beyond." *Quantum*, 2, 79 (2018). https://doi.org/10.22331/q-2018-08-06-79

3. Farhi, E., et al. "A Quantum Approximate Optimization Algorithm." arXiv:1411.4028 [quant-ph] (2014). https://arxiv.org/abs/1411.4028

4. Qiskit Textbook contributors. "Variational Quantum Algorithms." Qiskit Textbook. https://qiskit.org/textbook (accessed 2026).

5. Endre, A., et al. "Quantum-Inspired Optimization for Industrial Scale Problems." arXiv:2305.02179 [quant-ph] (2023). https://arxiv.org/abs/2305.02179

6. World Bank. "Venezuela RB - Overview." World Bank Country Overview. https://www.worldbank.org/en/country/venezuela/overview (accessed 2026).
