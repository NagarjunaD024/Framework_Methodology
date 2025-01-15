# Framework_Methodology
 Dematel and ISM
ISM and DEMATEL Analysis Notebooks

Overview

This repository contains two Jupyter notebooks:

ISM.ipynb - Implements Interpretive Structural Modeling (ISM).

DEMATEL.ipynb - Implements Decision-Making Trial and Evaluation Laboratory (DEMATEL).

These notebooks analyze survey data to generate metrics and visualizations for factor analysis. Both methods are useful for understanding and modeling complex systems and relationships among factors.

Prerequisites

Python (3.7 or higher)

Required Python libraries:

pandas

numpy

matplotlib

seaborn

jupyter

Install the required libraries using the following command:

pip install pandas numpy matplotlib seaborn jupyter

Workflow

1. Survey Data Input

Both notebooks require survey data as input. This data should represent:

Factors: Variables or elements being analyzed.

Relationships: Direct or indirect influences between factors.

2. ISM Notebook

Purpose: Constructs hierarchical structures to model relationships among factors.

Outputs:

Reachability Matrix: Summarizes the relationships between factors.

Structural Model Graph: Visual representation of factor hierarchies.

3. DEMATEL Notebook

Purpose: Evaluates the causal relationships and centrality of factors.

Outputs:

Influence Matrix: Captures direct and indirect influences among factors.

Causality vs. Centrality Plot: Visualizes the impact and role of each factor.

4. Generated Metrics and Visualizations

Both notebooks provide:

Tabular metrics summarizing relationships and hierarchies.

Graphical representations for clearer insights and interpretations.

Instructions for Use

Replace the placeholder survey data in the notebooks with your dataset. Ensure the format matches the expected structure described in the notebooks.

Run the notebooks step by step to:

Process the input data.

Compute the metrics.

Generate graphs and plots.

Review the outputs for insights into factor relationships and influence.

Results Interpretation

ISM Results:

Identifies hierarchical relationships among factors.

Shows which factors drive the system and which are dependent.

DEMATEL Results:

Highlights cause-and-effect relationships.

Differentiates between key driving factors and dependent factors.
