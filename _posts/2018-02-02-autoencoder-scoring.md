---
title: Autoencoder Scoring
date: 2018-02-02 15:27:31
---

## Motivation
Recent works use autoencoder's reconstruction error to measure how well autoencoder can represent the data.

Usually, the measure is reconstruction error, from the perspective of probabilistic model.

<p class="text-justify">In this paper, the authors shown that autoencoder can assign scores that are independently with training procedures and it can seen from a dynamic system instead of probabilistic model.</p>


## Background
<p>Training is to infer the latent representation from data which can be used for other tasks. Training AE is an unsupervised precedure. Typically, the features are useful for all classes.</p>

<p>Although probabilistic models may be used to extract class-independent features for classification, it has been more common to train one model per class and to subsequently use Bayes'rule for classification.</p>

<p>Here probabilistic models are often refered as RBM-based model. In these models negative energy can represent the score.</p>

## Details
Need to be finish.