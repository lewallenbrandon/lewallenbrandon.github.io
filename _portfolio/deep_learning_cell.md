---
title: "Deep Learning - Predicting DNA, RNA, and Protein Covariance in Single Cells with Deep Learning"
excerpt: "In this project, I explored with a team how Deep Learning could be applied to single cell analysis and used to effectively predict protein levels from RNA expression and RNA gene expression from chromatin accessibility."
collection: portfolio
---

# Project Summary: Advancing Single-Cell Analysis through Deep Learning

In our project, we tackled single-cell analysis, studying individual cells for insights into cellular processes and healthcare applications. Aligned with the **Human Cell Atlas** initiative, we joined a competition hosted by organizations like **Cellarity** and **Chan Zuckerberg Biohub**.

## Competition Tasks and Focus

The competition aimed to predict how **bone marrow stem cells** develop into blood cells using **DNA**, **RNA**, and **protein measurements**:

1. **CITEseq Task**: Predict protein levels from RNA expression.
2. **Multiome Task**: Predict RNA gene expression from chromatin accessibility.

## Methodology and Contributions

We used deep learning to handle sparse data, including:

- Reimplementing second-place solutions.
- Creating **LSTM**, **embedding**, and **attention-based models**.
- Experimenting with loss functions and model tuning.

We aimed for high **Pearson correlation scores**, measuring linear association between predicted and actual values.

## Achievements and Results

Our models performed well:

- Outperforming complex solutions with simpler architectures.
- Devising a novel **bilinear layer** ensemble strategy.

## Overcoming Challenges and Future Directions

Despite framework translation and sparse data challenges, we showcased how deep learning is effective when applied to single-cell analysis for disease diagnosis, drug discovery, and understanding cellular development. Future work includes exploring **transformer models** and **positional encoding**.

