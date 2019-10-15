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

[\[PDF\]](https://jiaruiqin.me)

### Abstract
Sequential recommendation task aims to predict user preferenceover items in the future given user historical behaviors. The or-der of user behaviors implies that there are resourceful sequentialpatterns embedded in the behavior history which reveal the underly-ing dynamics of user interests. Various sequential recommendationmethods are proposed to model the dynamic user behaviors. How-ever, most of the models only consider the user’s own behaviorsand dynamics, while ignoring the collaborative relations amongusers and items, i.e., similar tastes of users or analogous propertiesof items. Without modeling collaborative relations, those methodssuffer from the lack of recommendation diversity and thus mayhave worse performance. Worse still, most existing methods onlyconsider the user-side sequence and ignore the temporal dynamicson the item side. To tackle the problems of the current sequen-tial recommendation models, we proposeSequentialCollaborativeRecommender (SCoRe) which effectively mines high-order collabo-rative information using cross-neighbor relation modeling and, ad-ditionally utilizes both user-side and item-side historical sequencesto better capture user and item dynamics. Experiments on threereal-world yet large-scale datasets demonstrate the superiority ofthe proposed model over strong baselines.