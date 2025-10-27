# Artificial Intelligence from the Lens of Fairness — Simulation Code

Reproducible simulation framework.  
Implements a factorial design with **3 bias sources (F1–F3)** × **3 bias levels** × **2 access levels** × **2 interventions** × **2 model types** (logistic, tree).

**Factors**
- Bias sources: structural (F1), nonlinear (F2), asymmetric label noise (F3)
- Bias levels: low / med / high
- Access: full / none
- Interventions: none / postprocess (Equalized Odds)
- Models: logistic regression, decision tree

**Main artifact**
- `fairness_simulation.ipynb` — end-to-end notebook (simulate → summarize → plots). Open on GitHub or run in Colab/Jupyter.

**Quick start**
1. Clone or download this repo.
2. Open `fairness_simulation.ipynb` and **Run All**.
3. Outputs: `results.csv`, summary tables (accuracy/SPD/EOD), and figures.

**Requirements**
python>=3.10,<3.13
numpy>=1.24
pandas>=2.0
scikit-learn>=1.3
matplotlib>=3.7
seaborn>=0.13

