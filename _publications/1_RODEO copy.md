---
title: "RODEO: Robust Outlier Detection via Exposing Adaptive Out-of-Distribution Samples"
collection: publications
category: conferences
permalink: /publications/RODEO2
excerpt: 'In this work, we designed a novel method to detect outliers in adversarial settings. We were able to achieve state-of-the-art results on various tasks of outlier detection by generating adaptive outliers and expose them while training the anomaly detector adversarially.'
date: 2024-07-21
venue: 'ICML'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://proceedings.mlr.press/v235/mirzaei24a.html'
authors: 'Hossein Mirzaei, Mohammad Jafari, Hamid Reza Dehbashi, <strong>Ali Ansari</strong>, Sepehr Ghobadi, Masoud Hadi, Arshia Soltani Moakhar, Mohammad Azizmalayeri,
<a href="https://sharif.edu/~soleymani/">Mahdieh Soleymani Baghshah</a>,
<a href="https://sharif.ir/~rohban/">Mohammad Hossein Rohban</a>'
---

![Main figure of the paper](../images/rodeo_figure.png)

In recent years, there have been significant improvements in various forms of image outlier detection. However, outlier detection performance under adversarial settings lags far behind that in standard settings. This is due to the lack of effective exposure to adversarial scenarios during training, especially on unseen outliers, leading detection models failing to learn robust features. To bridge this gap, we introduce RODEO, a data-centric approach that generates effective outliers for robust outlier detection. More specifically, we show that incorporating outlier exposure (OE) and adversarial training could be an effective strategy for this purpose, as long as the exposed training outliers meet certain characteristics, including diversity, and both conceptual differentiability and analogy to the inlier samples. We leverage a text-to-image model to achieve this goal. We demonstrate both quantitatively and qualitatively that our adaptive OE method effectively generates ''diverse'' and ''near-distribution'' outliers, leveraging information from both text and image domains. Moreover, our experimental results show that utilizing our synthesized outliers significantly enhances the performance of the outlier detector, particularly in adversarial settings.