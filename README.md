# A Computational Model of Teacher–Student Co-Adaptation

Simulation code for the paper:

> **A Computational Model of Teacher–Student Co-Adaptation**  
> Francesco Balzan, Pedro P. Santos, Maurizio Gabbrielli, Mahault Albarracin, Manuel Lopes  
> *Computers and Education Open* (under review)

## Overview

This repository contains the simulation code for a Bayesian computational 
framework that studies co-adaptive teacher–student interaction under partial 
observability. The framework compares five interaction modes in a stylized 
concept-learning task with heterogeneous student groups.

## Requirements

- Python 3.8+
- NumPy
- Matplotlib
- Seaborn
- Pandas (for summary tables)

## Usage

The entire simulation runs in a single Jupyter notebook:
```bash
jupyter notebook simulation.ipynb
```

Alternatively, open directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/teacher-student-co-adaptation/blob/main/simulation.ipynb)

## Experimental Configuration

| Parameter | Value |
|-----------|-------|
| Features | 15 (binary) |
| Candidate concepts | 500 (filtered for learnability) |
| Student types | 3 (each blind to 5 features) |
| Groups | 3 × 30 students |
| Runs per condition | 100 |
| Random seed | 45 |

## License

MIT License
