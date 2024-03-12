---
title: An Edge-Aware Graph Autoencoder Trained on Scale-Imbalanced Data for Traveling Salesman Problems

authors:
- admin
- Xueming Yan
- Yaochu Jin

date: '2024-03-05'

doi: ''

publishDate: '2024-02-17T11:52:17.736087Z'

publication_types: ['article-journal']

publication: '*Knowledge-Based Systems*'


abstract: In recent years, there has been a notable surge in research on machine learning techniques for combinatorial optimization. It has been shown that learning-based methods outperform traditional heuristics and mathematical solvers on the Traveling Salesman Problem (TSP) in terms of both performance and computational efficiency. However, most learning-based TSP solvers are primarily designed for fixed-scale TSP instances, and also require a large number of training samples to achieve optimal performance. To fill this gap, this work proposes a data-driven graph representation learning method for solving TSPs with various numbers of cities. Specifically, we formulate the TSP as a link prediction task and propose an edge-aware graph autoencoder (EdgeGAE) model that can solve TSPs by learning from various-scale samples with an imbalanced distribution. A residual gated encoder is trained to learn latent edge embeddings, followed by an edge-centered decoder to output link predictions in an end-to-end manner. Furthermore, we introduce an active sampling strategy into the training process to improve the model’s generalization capability in large-scale scenarios. To investigate the model’s practical applicability, we generate a scale-imbalanced dataset comprising 50,000 TSP instances ranging from 50 to 500 cities. The experimental results demonstrate that the proposed edge-aware graph autoencoder model achieves a highly competitive performance among state-of-the-art graph learning-based approaches in solving TSPs with various scales, implying its remarkable potential in dealing with practical optimization challenges.

# Summary. An optional shortened abstract.
summary: We solve the TSP as a link prediction task and propose an edge-aware graph autoencoder (EdgeGAE) model that can solve TSPs by learning from various-scale samples with an imbalanced distribution.

tags:
- Graph Neural Network
- Data-driven Optimization
- Non-IID Distribution
- Supervised Learning

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: 'https://github.com/Shiqing-Liu'
url_source: 'https://www.sciencedirect.com/science/article/abs/pii/S0950705124001941'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'EdgeGAE framework'
  focal_point: ''
  preview_only: false

## sliu 0312 to-do: associate this paper with slides or projects. Refer to the example conference paper.

---
