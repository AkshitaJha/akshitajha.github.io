---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[CodeAttack: Code-based Adversarial Attacks for Pre-Trained Programming Language Models](https://arxiv.org/pdf/2206.00052.pdf), 2022 <br/>
**Akshita Jha**, Chandan K. Reddy

[Supervised Contrastive Learning for Interpretable Long-Form Document Matching](https://arxiv.org/pdf/2108.09190.pdf), **ACM Transactions on KDD**, 2022 <br/>
**Akshita Jha**, Vineeth Rakesh, Jaideep Chandrashekar, Adithya Samavedhi, Chandan K. Reddy

[Fair Representation Learning using Interpolation Enabled Disentanglement](https://arxiv.org/pdf/2108.00295.pdf), 2021 <br/>
**Akshita Jha**, Bhanukiran Vinzamuri, Chandan K. Reddy

[When does a Compliment become Sexist? Analysis and classification of Ambivalent Sexism using Twitter Data](https://aclanthology.org/W17-2902.pdf), NLP and CSS Workshop, **ACL 2017** <br/>
**Akshita Jha**, Radhika Mamidi

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
