---
title: "User Behavior Retrieval for Click-Through Rate Prediction"
collection: publications
permalink: /publication/UBR4CTR
excerpt: ''
date: 2020-5-10
venue: 'Proceedings of the 43th International ACM SIGIR Conference on Research and Development in Information Retrieval. (SIGIR 2020)'
# paperurl: '' 
# citation: ''
---

**Jiarui Qin**, Weinan Zhang, Xin Wu, Jiarui Jin, Yuchen Fang, Yong Yu

[\[PDF\]](https://arxiv.org/abs/2005.14171)

### Abstract
Click-through rate (CTR) prediction plays a key role in modern online personalization services. In practice, it is necessary to capture user's drifting interests by modeling sequential user behaviors to build an accurate CTR prediction model. However, as the users accumulate more and more behavioral data on the platforms, it becomes non-trivial for the sequential models to make use of the whole behavior history of each user. First, directly feeding the long behavior sequence will make online inference time and system load infeasible. Second, there is much noise in such long histories to fail the sequential model learning. The current industrial solutions mainly truncate the sequences and just feed recent behaviors to the prediction model, which leads to a problem that sequential patterns such as periodicity or long-term dependency are not embedded in the recent several behaviors but in far back history. To tackle these issues, in this paper we consider it from the data perspective instead of just designing more sophisticated yet complicated models and propose User Behavior Retrieval for CTR prediction (UBR4CTR) framework. In UBR4CTR, the most relevant and appropriate user behaviors will be firstly retrieved from the entire user history sequence using a learnable search method. These retrieved behaviors are then fed into a deep model to make the final prediction instead of simply using the most recent ones. It is highly feasible to deploy UBR4CTR into industrial model pipeline with low cost. Experiments on three real-world large-scale datasets demonstrate the superiority and efficacy of our proposed framework and models.