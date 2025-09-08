# AML MRD — Flow Cytometry Resources

> Ressources sélectionnées pour analyser la **maladie résiduelle mesurable (MRD)** dans les **leucémies aiguës myéloïdes (LAM)** par **cytométrie en flux** (CMF) : algorithmes et jeu de données

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#comment-contribuer)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)


## Table des matières
- [Qualité & prétraitement](#qualité--prétraitement)
- [Gating (manuel & automatique)](#gating-manuel--automatique)
- [Réduction de dimension et visualisation](#réduction-de-dimension-et-visualisation)
- [Outils & pipelines](#outils--pipelines)
- [Jeux de données publics](#jeux-de-données-publics)
- [Tutoriels & notebooks](#tutoriels--notebooks)
- [Articles clés & revues](#articles-clés--revues)
- [Comment contribuer](#comment-contribuer)
- [Licence & citation](#licence--citation)

---

## Qualité & prétraitement
### Normalisation
- **CytoNorm 2.0** — *A Flexible Normalization Framework for Cytometry Data without Requiring Dedicated Controls*.  
  *Cytometry Part A, Quintelier K.L.A., Willemsen M., Bosteels V., Aerts J.G.J.V., Saeys Y., Van Gassen S., (s.d.)*.  
  [DOI:10.1002/cyto.a.24910](https://doi.org/10.1002/cyto.a.24910)

## Gating (manuel & automatique)
- *(ex. stratégies AML MRD, openCyto, règles, modèles appris)*

## Réduction de dimension et visualisation
### Transport optimal
- **Transport optimal** — *Low Dimensional Representation of Multi‐Patient Flow Cytometry Datasets Using Optimal Transport for Measurable Residual Disease Detection in Leukemia*.  
  *Cytometry Part A, Gachon E., Bigot J., Cazelles E., et al., 2025*.  
  [DOI:10.1002/cyto.a.24918](https://doi.org/10.1002/cyto.a.24918)

- **Transport optimal** — *An Optimal Transport-Based Low-Dimensional Visualization Framework for High-Parameter Flow Cytometry*.  
  *Prépublication (Bioinformatics), Shemonti A., Gmyrek G.B., Quintelier K.L.A., et al., 24 août 2025*.  
  [DOI:10.1101/2025.08.19.670604](https://doi.org/10.1101/2025.08.19.670604)

### FlowSOM
- **FlowSOM (Self-Organizing Maps)** — *FlowSOM: Using Self-Organizing Maps for Visualization and Interpretation of Cytometry Data*.  
  *Cytometry Part A, Van Gassen S., Callebaut B., Van Helden M.J., et al., 2015*.  
  [DOI:10.1002/cyto.a.22625](https://doi.org/10.1002/cyto.a.22625)
- **FlowSOM (R)** — *An R-Derived FlowSOM Process to Analyze Unsupervised Clustering of Normal and Malignant Human Bone Marrow Classical Flow Cytometry Data*.  
  *Cytometry Part A, Lacombe F., Lechevalier N., Vial J.P., Béné M.C., 2019*.  
  [DOI:10.1002/cyto.a.23897](https://doi.org/10.1002/cyto.a.23897)

### Gaussian Mixture Models (GMM)
- **Computational MRD validation (HOVON-SAKK-132)** — *Computational measurable residual disease assessment in acute myeloid leukemia: A retrospective validation in the HOVON-SAKK-132 trial*.  
  *Leukemia, Mocking T.R., Haaksma L.H., Reuvekamp T., Kelder A., Scholten W.J., Ngai L.L., Breems D.A., Fischer T., Gjertsen B.T., Griškevičius L., Juliusson G., Maertens J.A., Manz M.G., Pabst T., Passweg J.R., Porkka K., Valk P.J.M., Gradowska P., Löwenberg B., Bachas C., 2025*.  
  [DOI:10.1038/s41375-025-02747-8](https://doi.org/10.1038/s41375-025-02747-8)
  💡 *Une évaluation rétrospective de l'algorithme GMMc de Mocking et al. sur la cohorte HOVON-SAKK-132, qui montre une meilleure prédiction de la rechute que la méthode manuelle. À noter : seuil "custom" dont la fixation entraîne peut-être un risque d’overfitting.*


## Outils & pipelines

- **MAGIC-DR** — *An Interpretable Machine-Learning Guided Approach for Acute Myeloid Leukemia Measurable Residual Disease Analysis*.  
  *Cytometry Part B: Clinical Cytometry, Shopsowitz K., Lofroth J., Chan G., et al., 2024*.  
  [DOI:10.1002/cyto.b.22168](https://doi.org/10.1002/cyto.b.22168)
  
- **Mixture Models for MRD** — *Computational Assessment of Measurable Residual Disease in Acute Myeloid Leukemia Using Mixture Models*.  
  *Communications Medicine, Mocking T.R., Kelder A., Reuvekamp T., et al., 2024*.  
  [DOI:10.1038/s43856-024-00700-x](https://doi.org/10.1038/s43856-024-00700-x)

## Jeux de données publics
- **FlowCAP / DREAM AML dataset (FR-FCM-ZZYA)** — Jeu de données de cytométrie en flux (FCS) utilisé dans les challenges **FlowCAP** et **DREAM** pour l’évaluation comparative des méthodes d’analyse automatisée.  
  Contient plusieurs centaines d’échantillons (AML vs non-AML, diagnostics de leucémie aiguë myéloïde et témoins), avec panels multicolores standards.  
  Sert de **benchmark de référence** pour tester et comparer les algorithmes de gating, clustering et classification appliqués à la MRD en LAM.  
  *Référence* : Aghaeepour N., Finak G., FlowCAP Consortium, DREAM Consortium, et al. *Critical Assessment of Automated Flow Cytometry Data Analysis Techniques*. **Nature Methods**, 10(3):228-38, 2013.  
  [DOI:10.1038/nmeth.2365](https://doi.org/10.1038/nmeth.2365) · [FlowRepository FR-FCM-ZZYA](http://flowrepository.org/id/FR-FCM-ZZYA)

## Tutoriels & notebooks
- *(guides pas-à-pas, cours, ateliers)*

## Articles clés & revues

- **Review ML for MRD** — *Applications of Machine Learning for Immunophenotypic Measurable Residual Disease Assessment in Acute Myeloid Leukemia*.  
  *HemaSphere, Mocking T.R., van de Loosdrecht A.A., Cloos J., Bachas C., 2025*.  
  [DOI:10.1002/hem3.70138](https://doi.org/10.1002/hem3.70138)


---

## Comment contribuer
Les contributions ne sont pas encore possible, mais ça va venir...

## Licence & citation
- Contenu : [MIT License](./LICENSE).
- Pour citer ce dépôt, utilisez le fichier [`CITATION.cff`](./CITATION.cff).
