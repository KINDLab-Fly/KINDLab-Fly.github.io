---
title: "Towards Well-rounded Graph Retrieval for Retrieval-augmented Generation"
layout: textlay
excerpt: "Towards Well-rounded Graph Retrieval for Retrieval-augmented Generation"
sitemap: false
permalink: /projects/nsf-III-GraphRAG/
---

# Towards Well-rounded Graph Retrieval for Retrieval-augmented Generation

![]({{ site.url }}{{ site.baseurl }}/images/research/NSF-III-GraphRAG.png){: style="width: 700px; height: auto; display: block; margin: 20px auto;" }

## Project Description

Solutions to real-world problems, such as scientific document question-answering, cybersecurity diagnosis, and e-commerce personalization, can often be improved by augmenting the underlying generative artificial intelligence-based (Gen-AI) systems with retrieved external knowledge. Much of this external knowledge is organized in graph-structured formats that encode unique relational signals. For example, citation links among scientific papers reveal their deep intellectual dependencies across different fields. Recurring co-occurrences among software components and vulnerability reports can reveal latent causal chains triggering security flaws. Online human interactions, such as liking, commenting, or reposting, reflect individual traits and preferences.

This project pioneers retrieval techniques that locate appropriate graph-structured knowledge and infuse it into Gen-AI systems to solve downstream problems, close knowledge gaps, and enable more useful, trustworthy, and diverse predictions, discovery, and decision-making. In personalization, the proposed retrieval techniques could give a social e-commerce platform a holistic view of each customer and support highly personalized recommendations. In cybersecurity, hidden dependencies among vulnerabilities and defenses could be exploited, allowing security operators to trace multi-step attack chains and harden critical systems against emerging threats. In scientific discovery and innovation, relational knowledge in graph-level retrieval can support exploration of multifaceted content and provide diverse insights that push existing knowledge boundaries.

To meet these goals, this project builds well-rounded graph retrieval techniques for retrieval-augmented generation (RAG) systems along three dimensions:

- **Utility:** Harmonize structured knowledge in graphs with neural knowledge in large language models through structured knowledge checking, evolving retrieval emphasis, and agentic multi-round graph traversal.
- **Trustworthiness:** Retrieve error-controlled graph-structured knowledge, disclose vulnerabilities through structure-informed threat models, and improve safety with data-centric and model-centric filtering.
- **Diversity:** Promote multi-agent collaborative exploration at both conceptual subgraph and individual entity levels.

Together, these innovations advance graph algorithms, retrieval modeling, and graph-structured knowledge representations for impactful domains such as healthcare, scientific innovation, personalization, cyber defense, and targeting.

## Publications

- [RAG vs. GraphRAG: A Systematic Evaluation and Key Insights](https://arxiv.org/abs/2502.11371)\
Kai Guo, Harry Shomer, Shenglai Zeng, Haoyu Han, Yu Wang, Jiliang Tang.\
ACM SIGKDD Conference on Knowledge Discovery and Data Mining, Dataset and Benchmark Track (KDD), 2026.

- [Empowering GraphRAG with Knowledge Filtering and Integration](https://aclanthology.org/2025.emnlp-main.1293/)\
Haoyu Han, Harry Shomer, Yu Wang, Yongjia Lei, Kai Guo, Zhigang Hua, Bo Long, Hui Liu, Jiliang Tang.\
Findings of the Association for Computational Linguistics: EMNLP, 2025.

- [Mixture of Structural-and-Textual Retrieval over Text-rich Graph Knowledge Bases](https://aclanthology.org/2025.findings-acl.941/) [[Code]](https://github.com/Yoega/MoR)\
Yongjia Lei, Haoyu Han, Ryan A. Rossi, Franck Dernoncourt, Nedim Lipka, Mahantesh M. Halappanavar, Jiliang Tang, Yu Wang.\
Findings of the Association for Computational Linguistics: ACL, 2025.

- [A Graph Perspective to Probe Structural Patterns of Knowledge in Large Language Models](https://arxiv.org/abs/2505.19286) [[Code]](https://github.com/utkarshxsahu/kgc)\
Utkarsh Sahu, Zhisheng Qi, Yongjia Lei, Ryan A. Rossi, Franck Dernoncourt, Nesreen K. Ahmed, Mahantesh M. Halappanavar, Yao Ma, Yu Wang.\
arXiv, 2025.

- [Topology-aware Retrieval Augmentation for Text Generation](https://dl.acm.org/doi/abs/10.1145/3627673.3679746)\
Yu Wang, Nedim Lipka, Ruiyi Zhang, Alexa Siu, Yuying Zhao, Bo Ni, Xin Wang, Ryan Rossi, Tyler Derr.\
ACM International Conference on Information and Knowledge Management (CIKM), 2024.

- [Knowledge Graph Prompting for Multi-Document Question Answering](https://ojs.aaai.org/index.php/AAAI/article/view/29889)\
Yu Wang, Nedim Lipka, Ryan A. Rossi, Alexa Siu, Ruiyi Zhang, Tyler Derr.\
AAAI Conference on Artificial Intelligence (AAAI), 2024.

- [Knowledge Graph-based Session Recommendation with Session-Adaptive Propagation](https://dl.acm.org/doi/abs/10.1145/3589335.3648324)\
Yu Wang, Amin Javari, Janani Balaji, Walid Shalaby, Tyler Derr, Xiquan Cui.\
ACM Web Conference (WWW), 2024.

- [Collaboration-Aware Graph Convolutional Network for Recommender Systems](https://arxiv.org/abs/2207.06221)\
Yu Wang, Yuying Zhao, Yi Zhang, Tyler Derr.\
ACM Web Conference (WWW), 2023.

## Resources

- [Retrieval-Augmented Generation with Graphs (GraphRAG)](https://arxiv.org/abs/2501.00309v1) [[Paper List]](https://github.com/Graph-RAG/GraphRAG/)\
Yu Wang, Haoyu Han, Harry Shomer, Kai Guo, Jiayuan Ding, Yongjia Lei, Mahantesh Halappanavar, Ryan A. Rossi, Subhabrata Mukherjee, Xianfeng Tang, Qi He, Zhigang Hua, Bo Long, Tong Zhao, Neil Shah, Amin Javari, Yinglong Xia, Jiliang Tang.\
arXiv, 2025.

- [Towards Trustworthy Retrieval Augmented Generation for Large Language Models: A Survey](https://arxiv.org/abs/2502.06872) [[Paper List]](https://github.com/Arstanley/Awesome-Trustworthy-RAG)\
Bo Ni, Zheyuan Liu, Leyao Wang, Yongjia Lei, Yuying Zhao, Xueqi Cheng, Qingkai Zeng, Luna Dong, Yinglong Xia, Krishnaram Kenthapadi, Ryan Rossi, Franck Dernoncourt, Md Mehrab Tanjim, Nesreen Ahmed, Xiaorui Liu, Wenqi Fan, Erik Blasch, Yu Wang, Meng Jiang, Tyler Derr.\
arXiv, 2025.

## Tutorials and Workshops

- [Retrieval-augmented Generation on Graph-structured Data](https://kindlab-fly.github.io/tutorials/sdm25/)\
Yu Wang, Haoyu Han, Harry Shomer, Kai Guo, Yongjia Lei, Jiayuan Ding, Xianfeng Tang, Qi He, Jiliang Tang.\
SIAM International Conference on Data Mining (SDM), 2025.

- [Machine Learning on Graphs in the Era of Generative Artificial Intelligence](https://mlgraphworkshop.github.io/)\
Yu Wang, Yu Zhang, Zhichun Guo, Harry Shomer, Haoyu Han, Tyler Derr, Nesreen Ahmed, Mahantesh Halappanavar, Jiliang Tang.\
ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2025.

## News and Awards

- Our NSF IIS-III Core Program project on developing foundational GraphRAG has been selected.
- Our paper, [Empowering GraphRAG with Knowledge Filtering and Integration](https://aclanthology.org/2025.emnlp-main.1293/), has been accepted at EMNLP 2025.
- Our survey on [Retrieval-Augmented Generation with Graphs (GraphRAG)](https://arxiv.org/abs/2501.00309v1) is online.
- The GraphRAG tutorial was presented at SDM 2025.

## Project Members

- [Yu Wang](https://yuwang0103.github.io/) (PI)
- [Yongjia Lei](https://github.com/Yoega) (Ph.D. student)
- [Zhisheng Qi](https://charlieqi02.github.io/) (Ph.D. student)
- [Utkarsh Sahu](https://scholar.google.com/citations?user=gBVVDhMAAAAJ&hl=en) (Ph.D. student)

## Collaborators

- **Academia:** Jiliang Tang, Hui Liu, Yao Ma, Tyler Derr, Harry Shomer, Haoyu Han, Kai Guo, Jiayuan Ding, Xianfeng Tang, Qi He, Tong Zhao, Neil Shah.
- **Industry and National Labs:** Ryan A. Rossi, Franck Dernoncourt, Nedim Lipka, Nesreen K. Ahmed, Mahantesh M. Halappanavar, Zhigang Hua, Bo Long.

## Acknowledgements

We thank all our academic and industrial collaborators for their support. This work is supported by the National Science Foundation through III 2524379. Any opinions, findings, conclusions, or recommendations expressed here are those of the authors and do not necessarily reflect the views of the National Science Foundation.

![]({{ site.baseurl }}/images/funding/NSF_logo_animation.gif)

## Contact

Yu Wang: Yu.Wang6@uga.edu
