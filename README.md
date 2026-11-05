# AI Group Assignment 2
DIVERSE_5
Course: Artificial Intelligence (2026)

## Group members

| Name | Roll number |
|---|---|
| (name 1) | (roll no.) |
| (name 2) | (roll no.) |
| (name 3) | (roll no.) |

## Contents

| Problem | Topic | Folder |
|---|---|---|
| 1 | Smart Home Energy Consumption Analysis using Bayesian Networks | [`problem1_smart_home/`](problem1_smart_home) |
| 2 | Mars Rover Sample Collection Planning using PDDL | [`problem2_mars_rover/`](problem2_mars_rover) |
| 3 | Royal Archive Access Verification using Resolution Refutation | [`problem3_royal_archive/`](problem3_royal_archive) |

```
.
├── README.md
├── problem1_smart_home/
│   ├── (notebook or .py file)
│   └── screenshots/
├── problem2_mars_rover/
│   ├── Domain.pddl
│   ├── Problem.pddl
│   ├── Problem_extended.pddl
│   ├── Mars_Rover_PDDL_Problem2.ipynb
│   ├── Analysis_Report.md
│   ├── planner_output/
│   ├── validation/
│   ├── validate_plan.py
│   └── screenshots/
└── problem3_royal_archive/
    ├── royal_archive_access.pl
    └── screenshots/
```

---

## Problem 1: Smart Home Energy Consumption Analysis using Bayesian Networks

A Bayesian Network models how weather, day type, occupancy, air-conditioner usage and appliance load affect household energy consumption.

- **Part A, expert network:** the network and its CPTs (each checked to sum to 1), a visualization, the queries Q1 to Q7, the explaining-away comparison of Q6 and Q7, and a hand calculation of Q1.
- **Part B, conditional independence:** d-separation analysis, checked numerically by inference.
- **Part C, synthetic data:** ancestral sampling with a fixed random seed, for 500, 5000 and 20000 samples.
- **Part D, learning:** parameters learned with MLE and with Bayesian Estimation (BDeu prior, equivalent sample size = 10).
- **Part E, comparison:** expert vs MLE vs Bayesian for Q1 to Q7, with the mean absolute difference plotted against dataset size.

**Files:** (list your files here, for example `smart_home_bn.ipynb`)
**Run:** (for example: open the notebook in Colab and run all cells; required libraries: `pgmpy`, `networkx`, `matplotlib`)

## Problem 2: Mars Rover Sample Collection Planning using PDDL

The rover Curiosity (two storage bays, one drill, one one-way route) collects rocks from the exploration sites and delivers them to Base. The problem is modelled in PDDL with only `:strips` and `:typing`, solved with the Fast# AI_ASSIGNMENT_2
DIVERSE_5
