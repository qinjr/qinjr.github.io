---
title: "Sequential Recommendation with Dual Side Neighbor-based Collaborative Relation Modeling"
collection: publications
permalink: /publication/SCORE
excerpt: ''
date: 2019-10-11
venue: 'Proceedings of the 13th ACM International Conference on Web Search and Data Mining. (WSDM 2020)'
# paperurl: '' 
# citation: ''
---

**Jiarui Qin**, Kan Ren, Yuchen Fang, Weinan Zhang, Yong Yu

[\[PDF\]](https://arxiv.org/abs/1911.03883)

### Abstract
Sequential recommendation task aims to predict user preference over items in the future given user historical behaviors. The order of user behaviors implies that there are resourceful sequential patterns embedded in the behavior history which reveal the underlying dynamics of user interests. Various sequential recommendation methods are proposed to model the dynamic user behaviors. However, most of the models only consider the user’s own behaviors and dynamics, while ignoring the collaborative relations among users and items, i.e., similar tastes of users or analogous properties of items. Without modeling collaborative relations, those methods suffer from the lack of recommendation diversity and thus may have worse performance. Worse still, most existing methods only consider the user-side sequence and ignore the temporal dynamics on the item side. To tackle the problems of the current sequential recommendation models, we propose Sequential Collaborative Recommender (SCoRe) which effectively mines high-order collaborative information using cross-neighbor relation modeling and, additionally utilizes both user-side and item-side historical sequences to better capture user and item dynamics. Experiments on three real-world yet large-scale datasets demonstrate the superiority of the proposed model over strong baselines.