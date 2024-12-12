---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- Journal
======
* test2 -->

International Conferences / Workshops (Refereed)
======
* Shun Inadumi, Seiya Kawano, Akishige Yuguchi, Yasutomo Kawanishi, Koichiro Yoshino: “A Gaze-grounded Visual Question Answering Dataset for Clarifying Ambiguous Japanese Questions”, The 2024 Joint International Conference on Computational Linguistics Language Resources and Evaluation (LREC-COLING2024), pp. 558-571, Torino, May. 2024.
  * [paper](https://aclanthology.org/2024.lrec-main.48/), [dataset](https://github.com/riken-grp/GazeVQA), [poster](http://sinadumi.github.io/files/202405_lrec_coling_poster.pdf)

International Conferences / Workshops (Non-refereed)
======
* Shun Inadumi, Seiya Kawano, Akishige Yuguchi, Yasutomo Kawanishi, Koichiro Yoshino: ”Question Disambiguation Using Eye-gaze Context”, Seventh International Workshop on Symbolic-Neural Learning (SNL2023), Tokyo, June. 2023.

Domestic Journals (Refereed)
======
* 稲積駿, 河野誠也, 湯口彰重,川西康友, 吉野幸一郎: ”Visual Question Answeringにおける視線情報を用いた質問の曖昧性解消”, 自然言語処理, vol. 32, no. 1, 2025年3月. [発行予定]

Domestic Conferences
======
* 稲積駿, 河野誠也, 湯口彰重,川西康友, 吉野幸一郎: ”Visual Question Answeringにおける視線情報を用いた質問の曖昧性解消”, 言語処理学会第30回年次大会 (NLP2024), 神戸, 2024年4月.

* 稲積駿, 河野誠也, 湯口彰重,川西康友, 吉野幸一郎: ”視覚的質問応答における視線情報を用いた曖昧な質問の明確化”, 第99回研究会言語・音声理解と対話処理研究会 (SIG-SLUD), 東京, 2023年12月.

* 稲積駿, 河野誠也, 湯口彰重,川西康友, 吉野幸一郎: ”視覚的質問応答における視線情報を利用した曖昧性解消に向けて”, 言語処理学会第29回年次大会 (NLP2023), 沖縄, 2023年3月.

* 稲積駿, 河野誠也, 湯口彰重,川西康友, 吉野幸一郎: ”視線情報付き視覚的質問応答データセットの構築”, 第96回研究会言語・音声理解と対話処理研究会 (SIG-SLUD), 東京, 2022年12月.

* 稲積駿, 石川秀大, 堀尾恵一: ”粒子群最適化法を用いた魚群の個体間相互作用の最適化”, スマートインフォメディアシステム研究会 (SIS2019), vol. 119, no. 458, pp. 73-78, 2020年3月. [開催中止，技報発行あり]
