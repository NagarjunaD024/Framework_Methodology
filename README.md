
# README: ISM and DEMATEL Analysis Notebooks

## Overview
This repository contains two Jupyter notebooks:
1. **ISM.ipynb** - Implements Interpretive Structural Modeling (ISM).
2. **DEMATEL.ipynb** - Implements Decision-Making Trial and Evaluation Laboratory (DEMATEL).

These notebooks analyze survey data to generate metrics and visualizations for factor analysis. Both methods are useful for understanding and modeling complex systems and relationships among factors.

## Prerequisites
- Python (3.7 or higher)
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - jupyter

Install the required libraries using the following command:
```bash
pip install pandas numpy matplotlib seaborn jupyter
Workflow

1. Survey Data Input

Input survey data representing:

Factors: Variables being analyzed.

Relationships: Direct or indirect influences between factors.

2. ISM Notebook

Purpose: Models hierarchical relationships among factors.

Outputs:

Reachability Matrix.

Structural Model Graph.

3. DEMATEL Notebook

Purpose: Evaluates causal relationships and factor centrality.

Outputs:

Influence Matrix.

Causality vs. Centrality Plot.

4. Generated Metrics and Visualizations

Both notebooks provide:

Tabular metrics summarizing relationships and hierarchies.

Graphical representations for insights and analysis.

Results Interpretation

ISM Results: Shows hierarchical relationships and driving vs. dependent factors.

DEMATEL Results: Highlights cause-and-effect relationships and factor roles
