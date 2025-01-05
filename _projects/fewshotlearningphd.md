---
layout: page
title: Few-shot Learning for ML Adaptation
description: My PhD thesis on investigating and developing few-shot learning solutions for more effective and more efficient machine learning model adaptation.
img: assets/img/EPFL_TH9878.pdf.jpg
importance: 2
category: [research]
selected: true
---

First, we investigate the existing linear regression meta-learning method R2D2 its reproducibility. We find that the findings are mostly reproducible, but different backbone models should be taken into consideration when comparing results of different methods.

Continuing with the methodology of linear regression, we introduce Regression Networks, a metric-learning few-shot classification approach. The metric is the embedded regression error of a point to a subspace of shots. Regression Networks achieve excellent results, especially when subspaces can be formed with multiple shots per class.

Subsequently, we address the inefficiency of needing many labeled training tasks by leveraging advances in self-supervised learning. Our approach ProtoTransfer has matching contrastive pre-training with prototypical task adaptation. We show that ProtoTransfer outperforms state-of-the-art unsupervised methods and even matches performance of supervised methods under domain-shift, at a fraction of the labeling cost.

Additionally, we design a meta-learning approach for survival analysis of rare diseases based on high-dimensional RNA sequencing data. Addressing parameter count, a firstorder meta-learning algorithm is adopted together with a Cox survival loss. We show that meta-learning is significantly more effective in this setting than regular fine-tuning.

Lastly, we go beyond single task adaptation with a model-agnostic learning to meta-learn (MALTML) approach. Our algorithm enables a model to quickly exploit commonalities among related tasks from an unseen task distribution, before quickly adapting to a specific task. Our experiments show that MALTML generally improves adaptation.
