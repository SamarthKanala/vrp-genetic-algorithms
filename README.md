# Optimization for Vehicle Routing Problem using Genetic Algorithms 🚚🧬

## Overview
This project applies **Genetic Algorithms (GA)** to solve the **Vehicle Routing Problem (VRP)** — a classic logistics and supply chain optimization challenge. Using Python’s **DEAP** evolutionary computation framework, the project also demonstrates GA’s flexibility by solving a **maze routing problem** before extending it to VRP.

## Features
- Developed GA-based optimization for VRP with **DEAP**.
- Designed a **custom fitness evaluation function** to minimize distance and cost.
- Experimented with mutation, crossover, and selection strategies.
- Implemented a **maze solver** to test GA approaches before applying to VRP.
- Visualized routing results with **Matplotlib**.

## Tech Stack
- **Python 3.10+**
- **DEAP** (Distributed Evolutionary Algorithms in Python)
- **Matplotlib** (visualizations)
- **NumPy** (numerical operations)
- *(Optional)* Pandas, Seaborn

## Results
- Optimized vehicle routing paths, reducing total travel distance.
- Demonstrated adaptability of GA in multiple problem contexts.
- Produced clear visualizations of optimal routes for decision-making.

## Project Structure
```
vrp-genetic-algorithms/
├── notebooks/
│   ├── maze_solver.ipynb   # GA applied to maze problem
│   └── vrp_ga.ipynb        # GA applied to VRP
├── src/
│   └── ga_solver.py        # Core GA implementation
├── results/
│   └── routes.png          # Example optimized routing plot
├── requirements.txt
└── README.md
```

## Installation & Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/vrp-genetic-algorithms.git
   cd vrp-genetic-algorithms
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks:
   - Open `notebooks/vrp_ga.ipynb`
   - Modify parameters (vehicles, customers, capacities, etc.)
   - Run all cells to see optimized routing and plots.

## References
- [DEAP Documentation](https://deap.readthedocs.io/)
- Blog post: [Your Blog Link Here]
- GitHub repo: [https://github.com/<your-username>/vrp-genetic-algorithms](https://github.com/<your-username>/vrp-genetic-algorithms)

---
