# Human-in-the-Loop (HITL): Algorithm's Interaction with Humans

## Overview

This document describes one of the six spheres from the Multidimensional Algorithm Structure (MAS) framework — **Human-in-the-Loop** — which explores how AI algorithms interact with humans within Human-Systems Integration (HSI) projects.

In this dimension, I aim to clarify the **degree and type of human involvement** required by various algorithms. This classification supports more informed algorithm selection in contexts that demand transparency, explainability, and trust.

---

## HITL Interaction Types

To enhance this dimension, I have introduced a refined categorization of algorithm interaction styles with humans. These categories allows the project to match algorithms to real-world HSI contexts more effectively.

| Type        | Description                                                                 | Examples of Algorithms                          | Application Scenarios                         |
|-------------|-----------------------------------------------------------------------------|------------------------------------------------|----------------------------------------------|
| **Direct**  | Human input is continuously required for operation or decision-making.       | Rule-based systems, Logistic Regression        | Clinical decision-making, control systems    |
| **Indirect**| Human input is provided periodically, often as feedback or tuning signals.   | Reinforcement Learning (feedback), Active Learning | Industrial automation, education platforms |
| **Opaque**  | Algorithm functions autonomously without user-facing explainability.         | Deep Neural Networks, CNNs, Black-box models   | Facial recognition, predictive policing      |
| **Auto**    | Fully automated with embedded explainability or interpretability features.   | SHAP with XGBoost, LIME with Random Forest     | Autonomous driving, decision-support systems |

---

## Mapping HITL Levels to MAS and XAI Goals

Each HITL interaction type plays a unique role in supporting Explainable AI (XAI) and Human-Systems Integration:

- **Direct**: Best for critical domains where decisions must be justified in real time.
- **Indirect**: Enables adaptive systems that learn from users while retaining autonomy.
- **Opaque**: Often powerful but risky in safety-critical environments due to low transparency.
- **Auto**: Ideal balance between autonomy and trust — crucial in industries like finance and healthcare.

---

## Contribution and Outcome

In this project, I:
- Designed the HITL dimension structure as part of the MAS framework
- Classified algorithms by HITL interaction types to improve algorithm selection logic
- Analyzed the role of HITL in increasing **trust** and **transparency** across **occupations** and **industries**
- Identified patterns in when and why different HITL levels are required in HSI projects

This framework strengthens the link between algorithm design and human-centered AI application goals, helping bridge the gap between usability, explainability, and technical performance.

---

## References

- O*NET Online Career Data – https://www.onetonline.org  
- NAICS Industry Data – https://www.census.gov/naics/  
- OpenML AI Algorithm Database – https://www.openml.org  
- SHAP, LIME, XGBoost documentation
