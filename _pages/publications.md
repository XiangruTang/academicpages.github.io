---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


[1]Xiangru Tang, Yujie Wang, Xianjun Shen. Categorizing Offensive Language in the Online World : A Chinese Corpus, Systems and an Explainable Tool. The 12th International Conference on Language Resources and Evaluation. 2020

[2]Xiangru Tang, Xinhui Tu. SYMGraph: A Neural Symbolic Approach with Numerically-Aware Graph forDiscrete Reasoning. The AAAI 2020 Workshop on Reasoning for Complex Question Answering. 2020.

[3]Liang Pang, Yanyan Lan, Xiangru Tang, Jiafeng Guo and Xueqi Cheng. An Empirical Study of Interpretability via Predictive-Descriptive Curve. (Under Review)

[4]Xiangru Tang, Yanyan Lan, Liang Pang, Changying Hao and Xueqi Cheng. A Benchmark of the Interpretability of Deep Learning Models. The 25th China Conference on Information Retrieval, 2019.

[5]Xiangru Tang, Po Hu. Knowledge-Aware Self-Attention Networks for Document Grounded Dialogue Generation. In International Conference on Knowledge Science, Engineering and Management, 2019. (oral)

[6]Xiangru Tang, Zhihao Wang, Jiyang Qi, Zengyang Li. Improving Code Generation From Descriptive Text By Combining Deep Learning and Syntax Rules. The 31st international conference on Software engineering and knowledge engineering, 2019. (oral)

[7]Xiangru Tang, Hanning Gao and Junjie Gao. Knowledge-based Factoid Question Generation with Seq2Seq Learning. The 2018 IEEE International Conference on Progress in Informatics and Computing, 2018. (oral and Best Paper Award)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
