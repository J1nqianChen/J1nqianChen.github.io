---
layout: homepage
---

## About Me {#about}

I am a Ph.D. student at Xi'an Jiaotong University, advised by [Prof. Jihua Zhu](https://gr.xjtu.edu.cn/web/zhujh). I received my bachelor's degree in software engineering from Xi'an Jiaotong University in 2021.

## Research Interests

Federated learning, uncertainty estimation, multimodal learning, and point cloud processing.

## News {#news}

- **Nov. 2026** — Posted the preprint [Same Rank, Different Needs](#same-rank).
- **Nov. 2026** — [Mitigating Generator Bias](#generator-bias) appeared in *IEEE Transactions on Artificial Intelligence*.
- **Sept. 2026** — [FedReCall](#fedrecall) was accepted to NeurIPS 2026 (co-first author).
- **Mar. 2026** — [Pseudo Multi-view K-means Clustering](#pmkc) appeared in the AAAI 2026 proceedings.
- **May 16, 2024** — [MFL-AKD](#mfl-akd) was accepted to IJCAI 2024.
- **Dec. 19, 2023** — [Watch Your Head](#aph) was accepted to AAAI 2024.
- **Jul. 26, 2023** — [FedKA](#fedka) was accepted to ACM Multimedia 2023.

## Publications {#publications}

{% assign papers_by_year = site.data.publications.published | group_by: "year" %}
{% for group in papers_by_year %}
<h3 class="publication-year">{{ group.name }}</h3>
{% include publications.html entries=group.items %}
{% endfor %}

## Preprints {#preprints}

{% include publications.html entries=site.data.publications.preprints %}

## Contact {#contact}

[{{ site.email }}](mailto:{{ site.email }})
