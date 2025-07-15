---
date: "2025-04-26T00:00:00Z"
external_link: ""
image:
  caption: ""
  focal_point: Smart
slides: ""
summary: Learning multiomic velocities of single cells by latent neural ODEs
tags:
- DynaVelo
title: DynaVelo
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

We present DynaVelo, a generative neural ordinary differential equation (ODE) model that learns the joint dynamics of gene expression and transcription factor (TF) motif activities in evolving cell systems using single-cell multiome data. DynaVelo leverages partial RNA velocity information together with single-cell TF motif accessibility data to improve the modeling of cell state dynamics and identification of TF drivers. We show that DynaVelo recovers the complex and bifurcating in vivo dynamics of wildtype murine germinal center (GC) B cells and reveals how these cell dynamics change under loss-of-function mutations in epigenetic regulators. DynaVelo resolves how TF motif activities evolve along latent time trajectories using analysis of training cells or through generated trajectories from the model. In silico perturbation analysis further enables DynaVelo to infer dynamic and cell-state-specific gene regulatory networks (GRNs), recovering many known TF-to-gene edges in the wildtype GC GRN and predicting those that are disrupted in mutants. Finally, in silico gene and TF perturbations allow both the prediction of cell dynamics under loss-of-function genetic mutations and the identification of TF perturbations to rescue loss-of-function dynamic and immunological phenotypes. DynaVelo therefore provides a powerful new deep learning framework for modeling and perturbing dynamic cell systems by harnessing single-cell multiome data sets.