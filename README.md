# Football Tactics Evolution using Genetic Algorithms

This project implements an evolutionary AI agent that optimizes football team tactics through a Genetic Algorithm (GA). It focuses on evolving key tactical parameters—pressing intensity, compactness, and line height—to improve match performance across goals scored, possession percentage, and passing accuracy.

---

## 🔍 Problem Statement

Traditional football tactics rely on static strategies and human intuition. This project uses evolutionary computing to dynamically optimize team behaviors for better match results. It simulates matches, evaluates tactical setups using a fitness function, and iteratively evolves strategies over multiple generations.

---

## 🚀 Features

- Optimizes tactics using Genetic Algorithm across 20 generations
- Tactical parameters: Pressing Intensity, Compactness, Line Height
- Match simulation for evaluating fitness
- Visualizations of match statistics, fitness evolution, and formation changes

---

## ⚙️ Methodology

### Genetic Algorithm Components:
- **Population:** Set of random tactics
- **Fitness Function:** `(Goals × 20) + (Shots on Target × 10) + (Possession × 5) + (Pass Completion × 2)`
- **Crossover & Mutation:** To generate new tactics
- **Selection:** Based on fitness score

### Tactical Parameters:
- **Pressing Intensity**: 1–10 scale
- **Compactness**: 1–10 scale
- **Line Height**: 1–10 scale

---

## 📊 Results

- **Goal scoring increased by 85%**
- **Possession improved by 13%**
- **Passing accuracy improved by 10%**
- **4-3-3 evolved formation outperformed baseline 4-4-2**

---

## 📁 Files

- `Football_Tactics_Evolution.ipynb`: Main implementation notebook
- `Football_Tactics_Evolution Report.pdf`: Full academic report with experiments and analysis
- `README.md`: Project overview

---

## 📈 Future Work

- Real-player datasets for validation
- Integration with Reinforcement Learning for live tactical changes
- Graph-based tactical optimization using GNNs

---

## 🧠 Citation

If you use this project, please cite the accompanying academic report:

> Mohamed Elsaygh. *Optimizing Football Tactics Using Evolutionary Algorithms*. MSc Dissertation, 2025.

---

## 👤 Author

- Mohamed Elsaygh
- MSc Artificial Intelligence, University of Sussex
