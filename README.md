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

> **Format des entrées** :  
> `- **Nom** — description courte. *Langage/Type* · *Catégorie*. [Lien principal] · [Doc] · [Article] · [Données]`

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

## Outils & pipelines

- **MAGIC-DR** — *An Interpretable Machine-Learning Guided Approach for Acute Myeloid Leukemia Measurable Residual Disease Analysis*.  
  *Cytometry Part B: Clinical Cytometry, Shopsowitz K., Lofroth J., Chan G., et al., 2024*.  
  [DOI:10.1002/cyto.b.22168](https://doi.org/10.1002/cyto.b.22168)
  
- **Mixture Models for MRD** — *Computational Assessment of Measurable Residual Disease in Acute Myeloid Leukemia Using Mixture Models*.  
  *Communications Medicine, Mocking T.R., Kelder A., Reuvekamp T., et al., 2024*.  
  [DOI:10.1038/s43856-024-00700-x](https://doi.org/10.1038/s43856-024-00700-x)

## Jeux de données publics
- *(ex. dépôts FCS, jeux MRD annotés, benchmarks)*

## Tutoriels & notebooks
- *(guides pas-à-pas, cours, ateliers)*

## Articles clés & revues

- **Review ML for MRD** — *Applications of Machine Learning for Immunophenotypic Measurable Residual Disease Assessment in Acute Myeloid Leukemia*.  
  *HemaSphere, Mocking T.R., van de Loosdrecht A.A., Cloos J., Bachas C., 2025*.  
  [DOI:10.1002/hem3.70138](https://doi.org/10.1002/hem3.70138)


---

## Comment contribuer
Les contributions sont bienvenues !  
1. Consultez [CONTRIBUTING.md](./CONTRIBUTING.md).  
2. Ouvrez une *issue* pour suggérer un lien ou une section.  
3. Proposez une *pull request* (format d’entrée ci-dessus, liens vérifiés).  

## Licence & citation
- Contenu : [CC BY 4.0](./LICENSE).  
- Pour citer ce dépôt, utilisez le fichier [`CITATION.cff`](./CITATION.cff).
