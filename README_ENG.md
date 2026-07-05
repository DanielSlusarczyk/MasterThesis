[:poland: Wersja polska](README.md)

# Study of artificial intelligence explainability methods using feature importance analysis

**Master's thesis** — Warsaw University of Technology, Institute of Control and Industrial Electronics

- **Programme:** Applied Computer Science, specialisation Data Engineering and Multimedia
- **Author:** Daniel Ślusarczyk
- **Supervisor:** Grzegorz Sarwas, PhD Eng.
- **Place and year:** Warsaw 2025

Repository of a master's thesis. It contains the thesis itself and the source files used to develop the experimental part of the project.

---

## Abstract

<div align="justify">

The dynamic development of artificial intelligence observed in recent years, along with the growing complexity of modern machine learning models, has led to a significant challenge in understanding the exact way in which their outputs are generated. Many key decisions in high-risk sectors (medicine, transport, public administration) are made by systems whose exact operation is incomprehensible even to individuals with expert knowledge. Such models, referred to as black boxes, constitute solutions whose internal logic is too advanced both for end users and for algorithm designers to directly describe the causes of the obtained outputs. This situation, in the context of growing ethical and regulatory requirements (e.g., the right to explanation), has resulted in the emergence of the field of explainable artificial intelligence (XAI), whose aim is to enhance the interpretability of models. The newly established branch of artificial intelligence represents both a philosophy of designing more transparent machine learning solutions and a set of ready-made methods that leverage the intricate structure of popular algorithms to describe their properties, including the feature importance of generated predictions.

The subject of this thesis is the empirical evaluation of three popular explainable artificial intelligence techniques (LIME, PFI, SHAP) in the study of various machine learning models, including linear regression, decision trees, random forests, XGBoost, and multilayer perceptrons. As part of the project component, an experimental environment was developed to compare the quality, stability, and consistency of feature-importance results across test variants. The obtained results indicate that all techniques have a similar potential in identifying the most important predictors, yet they differ significantly in the detailed distribution of importance across the remaining features. The highest stability was achieved for the PFI and SHAP methods, whereas LIME in its global variant demonstrated limited justification for practical use. The thesis also highlights the impact of feature collinearity on the interpretability of models when applying the aforementioned techniques and identifies their limitations in this regard. The work concludes with an assessment of the practical usefulness of the discussed methods and an indication of future research directions.

</div>

## Keywords

`explainable artificial intelligence` · `feature importance` · `XAI techniques` · `SHAP` · `LIME` · `PFI`
