---
title: "Towards Well-rounded Graph Retrieval for Retrieval-augmented Generation"
layout: textlay
excerpt: "Towards Well-rounded Graph Retrieval for Retrieval-augmented Generation"
sitemap: false
permalink: /projects/nsf-III-GraphRAG/
---

# Towards Well-rounded Graph Retrieval for Retrieval-augmented Generation

![]({{ site.url }}{{ site.baseurl }}/images/research/NSF-III-GraphRAG.png){: style="width: 700px; height: auto; display: block; margin: 20px auto;" }

## Live Demo

Explore the interactive Graph-Agent-Demo below, or open it in a new tab: [Graph-Agent-Demo](https://graph-agent.graphagentintelligence.com/){: target="_blank" rel="noopener noreferrer" }.

<div class="project-demo-embed" style="width: 100%; max-width: 100%; height: 600px; margin: 24px 0 34px; border: 1px solid #d8dee7; border-radius: 6px; overflow: hidden; background: #f8f8f8; box-shadow: 0 8px 24px rgba(15, 23, 42, 0.08);">
  <iframe
    src="https://graph-agent.graphagentintelligence.com/"
    title="Graph-Agent-Demo"
    width="100%"
    height="600"
    loading="lazy"
    allowfullscreen
    style="width: 100%; height: 100%; border: 0; display: block;">
  </iframe>
</div>

## Project Description

Solutions to real-world problems, such as scientific document question-answering, cybersecurity diagnosis, and e-commerce personalization, can often be improved by augmenting the underlying generative artificial intelligence-based (Gen-AI) systems with retrieved external knowledge. Much of this external knowledge is organized in graph-structured formats that encode unique relational signals. For example, citation links among scientific papers reveal their deep intellectual dependencies across different fields. Recurring co-occurrences among software components and vulnerability reports can reveal latent causal chains triggering security flaws. Online human interactions, such as liking, commenting, or reposting, reflect individual traits and preferences. This project pioneers retrieval techniques that locate appropriate graph-structured knowledge and infuse it into Gen-AI systems to solve downstream problems, close knowledge gaps, and enable more useful, trustworthy, and diverse predictions, discovery, and decision-making. In personalization, the proposed retrieval techniques could give a social e-commerce platform a holistic view of each customer and support highly personalized recommendations. In cybersecurity, hidden dependencies among vulnerabilities and defenses could be exploited, allowing security operators to trace multi-step attack chains and harden critical systems against emerging threats. In scientific discovery and innovation, relational knowledge in graph-level retrieval can support exploration of multifaceted content and provide diverse insights that push existing knowledge boundaries. To meet these goals, this project builds well-rounded graph retrieval techniques for retrieval-augmented generation (RAG) systems along three dimensions:

- **Utility:** Harmonize structured knowledge in graphs with neural knowledge in large language models through structured knowledge checking, evolving retrieval emphasis, and agentic multi-round graph traversal.
- **Trustworthiness:** Retrieve error-controlled graph-structured knowledge, disclose vulnerabilities through structure-informed threat models, and improve safety with data-centric and model-centric filtering.
- **Diversity:** Promote multi-agent collaborative exploration at both conceptual subgraph and individual entity levels.

Together, these innovations advance graph algorithms, retrieval modeling, and graph-structured knowledge representations for impactful domains such as healthcare, scientific innovation, personalization, cyber defense, and targeting.

## Publications

- **Benchmarking Knowledge-Extraction Attack and Defense on Retrieval-Augmented Generation**\
Zhisheng Qi, Utkarsh Sahu, Li Ma, Haoyu Han, Ryan Rossi, Franck Dernoncourt, Mahantesh Halappanavar, Nesreen Ahmed, Yushun Dong, Yue Zhao, Yu Zhang, Yu Wang.\
ACM SIGKDD Conference on Knowledge Discovery & Data Mining, Dataset and Benchmark Track (KDD), 2026.\
[[Paper]](https://arxiv.org/abs/2602.09319) [[Code]](https://github.com/charlieqi02/RAG-Knowledge-Extraction-Attack-and-Defense-Benchmark)\
<span style="color:red">**Oral Presentation (4.5%)**</span>

- **RAG vs. GraphRAG: A Systematic Evaluation and Key Insights**\
Haoyu Han, Harry Shomer, Yu Wang, Yongjia Lei, Kai Guo, Zhigang Hua, Bo Long, Hui Liu, Jiliang Tang.\
ACM SIGKDD Conference on Knowledge Discovery & Data Mining, Dataset and Benchmark Track (KDD), 2026.\
[[Paper]](https://arxiv.org/abs/2502.11371) [[Code]](https://github.com/haoyuhan1/RAGvsGraphRAG)

- **Empowering GraphRAG with Knowledge Filtering and Integration**\
Kai Guo, Harry Shomer, Shenglai Zeng, Haoyu Han, Yu Wang, Jiliang Tang.\
Empirical Methods in Natural Language Processing (EMNLP), 2025.\
[[Paper]](https://aclanthology.org/2025.emnlp-main.1293/)

- **Building Transparency in Deep Learning-Powered Network Traffic Classification: A Traffic-Explainer Framework**\
Riya Ponraj, Ram Durairajan, Yu Wang.\
ACM SIGKDD Conference on Knowledge Discovery & Data Mining (KDD), 2026.\
[[Paper]](https://arxiv.org/abs/2509.18007) [[Code]](https://github.com/yuwvandy/NetExplainer)

- **Rule Mining and Learning for Structured Knowledge Retrieval**\
Yongjia Lei, Mahantesh M Halappanavar, Yu Wang.\
ACM International Conference on Web Search and Data Mining (WSDM), 2026.

- **Knowledge Homophily in Large Language Models**\
Utkarsh Sahu, Zhisheng Qi, Mahantesh M Halappanavar, Nedim Lipka, Ryan A Rossi, Franck Dernoncourt, Yu Zhang, Yao Ma, Yu Wang.\
ACM International Conference on Web Search and Data Mining (WSDM), 2026.\
[[Paper]](https://dl.acm.org/doi/10.1145/3773966.3779394) [[Code]](https://github.com/utkarshxsahu/kgc)

- **Towards Trustworthy Retrieval Augmented Generation for Large Language Models: A Survey**\
Bo Ni, Zheyuan Liu, Leyao Wang, Yongjia Lei, Yuying Zhao, Xueqi Cheng, Qingkai Zeng, Luna Dong, Yinglong Xia, Krishnaram Kenthapadi, Ryan Rossi, Franck Dernoncourt, Md Mehrab Tanjim, Nesreen Ahmed, Xiaorui Liu, Wenqi Fan, Erik Blasch, Yu Wang, Meng Jiang, Tyler Derr.\
ACM Computing Surveys (CSUR), 2026.\
[[Paper]](https://arxiv.org/abs/2502.06872) [[Code]](https://github.com/Arstanley/Awesome-Trustworthy-RAG)

- **Mixture of Structural-and-Textual Retrieval over Text-rich Graph Knowledge Bases**\
Yongjia Lei, Haoyu Han, Ryan A. Rossi, Franck Dernoncourt, Nedim Lipka, Mahantesh M. Halappanavar, Jiliang Tang, Yu Wang.\
Annual Meeting of the Association for Computational Linguistics (ACL), 2025.\
[[Paper]](https://aclanthology.org/2025.findings-acl.941/) [[Code]](https://github.com/Yoega/MoR)\
<span style="color:red">**Best Poster Honorable Mention at SDM'25 Doctoral Forum**</span>

## Preprints

- **Retrieval-Augmented Generation with Graphs (GraphRAG)**\
Yu Wang, Haoyu Han, Harry Shomer, Kai Guo, Jiayuan Ding, Yongjia Lei, Mahantesh Halappanavar, Ryan A. Rossi, Subhabrata Mukherjee, Xianfeng Tang, Qi He, Zhigang Hua, Bo Long, Tong Zhao, Neil Shah, Amin Javari, Yinglong Xia, Jiliang Tang.\
arXiv, 2025.\
[[Paper]](https://arxiv.org/abs/2501.00309v1) [[Paper List]](https://github.com/Graph-RAG/GraphRAG/)

- **RL-Index: Reinforcement Learning for Retrieval Index Reasoning**\
Yongjia Lei, Nedim Lipka, Zhisheng Qi, Utkarsh Sahu, Koustava Goswami, Franck Dernoncourt, Ryan A. Rossi, Yu Wang.\
arXiv, 2026.\
[[Paper]](https://arxiv.org/abs/2606.16316)

- **Benchmarking Multi-Modal Graph-Based Social Media Popularity Prediction**\
Utkarsh Sahu, Zhisheng Qi, Li Zhu, Yizhao Yang, Jun Li, Ryan Rossi, Yu Wang.\
arXiv, 2026.\
[[Paper]](https://arxiv.org/abs/2606.27539)

- **Sparse Personalized Text Generation with Multi-Trajectory Reasoning**\
Bo Ni, Haowei Fu, Qinwen Ge, Franck Dernoncourt, Samyadeep Basu, Nedim Lipka, Seunghyun Yoon, Yu Wang, Nesreen K. Ahmed, Subhojyoti Mukherjee, Puneet Mathur, Ryan A. Rossi, Tyler Derr.\
arXiv, 2026.\
[[Paper]](https://arxiv.org/abs/2604.24996)

## Tutorials and Workshops

### Workshops

- [**SURGeLLM: Structured Understanding, Retrieval, and Generation in LLMs era**](https://surgellm.github.io/acl2026/)\
Vivek Gupta, Kaize Ding, Harsha Kokel, Yue Zhao, Amit Agarwal, Yu Wang, Michael Glass, Yu Zhang, Kavitha Srinivas, Xiusi Chen, Oktie Hassanzadeh, Qi Zhu, Shuaichen Chang, Yuan Luo.\
Annual Meeting of the Association for Computational Linguistics (ACL), 2026.

- [**Machine Learning on Graphs in the Era of Generative Artificial Intelligence**](https://mlgraphworkshop.github.io/)\
Yu Wang, Yu Zhang, Zhichun Guo, Harry Shomer, Haoyu Han, Tyler Derr, Nesreen Ahmed, Mahantesh Halappanavar, Jiliang Tang.\
ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2025.

### Tutorials

- [**Rigorizing Retrieval-augmented Generation with Structural Intelligence**](https://kindlab-fly.github.io/tutorials/wsdm26/)\
Zhisheng Qi, Yongjia Lei, Haoyu Han, Harry Shomer, Kaize Ding, Yu Zhang, Ryan Rossi, Hui Liu, Yu Wang.\
ACM International Conference on Web Search and Data Mining (WSDM), 2026.

- [**Empowering Retrieval-augmented Generation with Graph-structured Knowledge**](https://kindlab-fly.github.io/tutorials/sdm25/)\
Yu Wang, Haoyu Han, Harry Shomer, Kai Guo, Yongjia Lei, Jiayuan Ding, Xianfeng Tang, Qi He, Jiliang Tang.\
SIAM International Conference on Data Mining (SDM), 2025.

## Awards and Honors

- Our NSF IIS-III Core Program project on developing foundational GraphRAG has been selected.
- Yu Wang received the SIGKDD 2025 Dissertation Award Honorable Mention.
- [Mixture of Structural-and-Textual Retrieval over Text-rich Graph Knowledge Bases](https://aclanthology.org/2025.findings-acl.941/) received Best Poster Honorable Mention at the SDM 2025 Doctoral Forum.
- Yongjia Lei received the UO Student OpenHouse 2025 Poster Honorable Mention.
- Yongjia Lei obtained the Adobe Research Summer Internship 2025.
- [Benchmarking Knowledge-Extraction Attack and Defense on Retrieval-Augmented Generation](https://arxiv.org/abs/2602.09319) was selected as a KDD 2026 Dataset and Benchmark Track oral presentation (4.5%).
- Zhisheng Qi received the UO Student OpenHouse 2026 Poster Runner-up award.
- Zhisheng Qi received the WSDM 2026 Student Travel Award.
- Utkarsh Sahu received the WSDM 2026 Student Travel Award.

## Core Project Members

- [Yu Wang](https://yuwang0103.github.io/) (PI)
- [Yongjia Lei](https://github.com/Yoega) (Ph.D. student)
- [Zhisheng Qi](https://charlieqi02.github.io/) (Ph.D. student)
- [Utkarsh Sahu](https://scholar.google.com/citations?user=gBVVDhMAAAAJ&hl=en) (Ph.D. student)

## Acknowledgements

We thank all our academic and industrial collaborators for their support. This work is supported by the National Science Foundation through III 2524379. Any opinions, findings, conclusions, or recommendations expressed here are those of the authors and do not necessarily reflect the views of the National Science Foundation.

![]({{ site.baseurl }}/images/funding/NSF_logo_animation.gif)

## Contact

Yu Wang: Yu.Wang6@uga.edu
