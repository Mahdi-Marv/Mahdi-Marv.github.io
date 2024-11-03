---
title: "A Contrastive Teacher-Student Framework for Novelty Detection under Style Shifts"
collection: publications
category: conferences
permalink: /publications/style-shift
excerpt: 'In this work, we designed a novelty detection method which is robust to style shifts in the data distribution. By distinguishing between core features and style features and using a teacher-student scheme, we were able to achieve state-of-the-art results on various dataset pairs.'
date: 2025-01-21
venue: 'Submitted to ICLR'
# paperurl: 'https://proceedings.mlr.press/v235/mirzaei24a.html'
authors: 'Hossein Mirzaei, Mojtaba Nafez, Moein Madadi, Arad Maleki, Mahdi Hajialilue, Zeinab Sadat Taghavi, Sepehr Rezaee, <strong>Ali Ansari</strong>, Bahar Dibaei Nia, Kian Shamsaie, Mohammadreza Salehi, Jafar Habibi, Mackenzie W Mathis,
<a href="https://sharif.edu/~soleymani/">Mahdieh Soleymani Baghshah</a>,
<a href="https://sabokrou.github.io/">Mohammad Sabokrou</a>,
<a href="https://sharif.ir/~rohban/">Mohammad Hossein Rohban</a>'
---

![Main figure of the paper](../images/style_shift_figure.jpg)

There have been several efforts to improve Novelty Detection (ND) performance. However, ND methods often suffer significant performance drops under minor distribution shifts caused by changes in the environment, known as style shifts. This challenge arises from the ND setup, where the absence of out-of-distribution (OOD) samples during training causes the detector to be biased toward the dominant style features in the in-distribution (ID) data. As a result, the model mistakenly learns to correlate style with core features, using this shortcut for detection. Robust ND is crucial for real-world applications like autonomous driving and medical imaging, where test samples may have different styles than the training data. Motivated by this, we propose a robust ND method that crafts an auxiliary OOD set with style features similar to the ID set but with different core features. Then, a task-based knowledge distillation strategy is utilized to distinguish core features from style features and help our model rely on core features for discriminating crafted OOD and ID sets. We verified the effectiveness of our method through extensive experimental evaluations on several datasets, including synthetic and real-world benchmarks, against nine different ND methods.