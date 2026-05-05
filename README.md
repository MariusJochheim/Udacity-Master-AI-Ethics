# AI Ethics Project – IDOOU Budget Predictor

This repository contains my AI Ethics project for evaluating and mitigating bias in a hypothetical IDOOU Budget Predictor AI system.

The project investigates whether a machine learning model can predict whether a user’s budget is `>=300` or `<300` for activity recommendations, while also assessing fairness risks related to education level.

## Project Overview

The IDOOU Budget Predictor is treated as a medium-risk personalization system. It does not make high-stakes decisions such as lending, hiring, healthcare, or legal eligibility decisions, but it can still affect the user experience by influencing which activities are recommended.

The project focuses on the following ethical AI questions:

- Is the dataset representative across demographic groups?
- Does the target variable show bias across education levels?
- Do machine learning models reproduce this bias?
- Can bias mitigation improve fairness?
- What should be documented in a model card before deployment?

## Repository Contents

```text
.
├── AI Ethics Project -- STARTER.ipynb
├── model_card.html
├── model_card_images/
│   ├── confusion_matrix_reweighed_lr.png
│   ├── accuracy_reweighed_lr.png
│   ├── interpretability_reweighed_lr.png
│   └── cohort_performance_by_education.png
└── README.md
