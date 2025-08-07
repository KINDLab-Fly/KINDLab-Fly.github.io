---
title: "nsf-III-GraphRAG"
layout: textlay
excerpt: "nsf-III-GraphRAG"
sitemap: false
permalink: /projects/nsf-III-GraphRAG/
---


## Towards Well-Rounded Graph Retrieval for RAG
![]({{ site.url }}{{ site.baseurl }}/images/research/NSF-III-GraphRAG.png){: style="width: 400px; height: auto; display: block; margin: 20px auto;" }

Solutions to real-world problems, such as scientific document question-answering, cybersecurity diagnosis, and e-commerce personalization, can often be improved by augmenting the underlying generative artificial intelligence-based (Gen-AI) systems with retrieved external knowledge. Much of this external knowledge is organized in graph-structured formats that encode unique relational signals. For example, citation links among scientific papers reveal their deep intellectual dependencies across different fields. Recurring co-occurrences among software components and vulnerability reports can reveal latent causal chains triggering security flaws. Online human interactions, such as liking, commenting, or reposting, reflect individual traits and preferences. This project pioneers retrieval techniques that locate the appropriate graph-structured knowledge and infuse it to assist Gen-AI systems with solving downstream problems, closing critical knowledge gaps, and enabling more useful, trustworthy, and diverse predictions, discovery, and decision-making. In personalization, the proposed retrieval techniques could give a social e-commerce platform a holistic view of each customer and support highly personalized recommendations. In cybersecurity, hidden dependencies among vulnerabilities and defenses could be exploited, allowing security operators to trace multi-step attack chains and harden critical systems against emerging threats. In scientific discovery and innovation, the relational knowledge in our proposed graph-level retrieval could facilitate exploration of multifaceted content and provide diverse insights that push existing knowledge boundaries.

To meet these goals, this project pioneers a transformative roadmap to build well-rounded graph retrieval techniques for retrieval-augmented generation (RAG) systems that advance three dimensions: (1) Improving utility by harmonizing knowledge between structured knowledge in graphs and neural knowledge in large language models via structured knowledge checking, aligning retrieval emphasis with user interests by estimating continuously evolving trends, and incorporating agentic planning and reasoning capabilities for intelligent multi-round graph-structured traversal; (2) Safeguarding trustworthiness by reliably retrieving error-controlled graph-structured knowledge, disclosing vulnerability by designing structure-informed threat models and improving safety with data-centric textual subgraph anomaly detection and model-centric neighborhood trend filtering; (3) Promoting knowledge diversity through multi-agent collaborative exploration at both the conceptual subgraph and individual entity level. Together, these innovations will yield theoretical advances in graph algorithms, retrieval modeling, and graph-structured knowledge representations, ultimately transforming how graph-structured knowledge is discovered, integrated, and applied in RAG and Gen-AI systems across impactful domains, such as healthcare, scientific innovation, personalization, cyber defense, and targeting.

### Publications
[Mixture of Structural-and-Textual Retrieval over Text-rich Graph Knowledge Bases](https://aclanthology.org/2025.findings-acl.941/)[code](https://github.com/Yoega/MoR) \
Yongjia Lei, Haoyu Han, Ryan A Rossi, Franck Dernoncourt, Nedim Lipka, Mahantesh M Halappanavar, Jiliang Tang, Yu Wang. \
https://aclanthology.org/2025.findings-acl.941/ (2025).

[A Graph Perspective to Probe Structural Patterns of Knowledge in Large Language Models](https://arxiv.org/abs/2505.19286)[code](https://github.com/utkarshxsahu/kgc) \
Utkarsh Sahu, Zhisheng Qi, Yongjia Lei, Ryan A. Rossi, Franck Dernoncourt, Nesreen K. Ahmed, Mahantesh M Halappanavar, Yao Ma, Yu Wang. \
https://arxiv.org/abs/2505.19286 (2025).

[Empowering GraphRAG with Knowledge Filtering and Integration](https://arxiv.org/abs/2503.13804) \
Haoyu Han, Harry Shomer, Yu Wang, Yongjia Lei, Kai Guo, Zhigang Hua, Bo Long, Hui Liu, Jiliang Tang. \
https://arxiv.org/abs/2502.11371 (2025).

[Rag vs. graphrag: A systematic evaluation and key insights](https://arxiv.org/abs/2502.11371) \
Kai Guo, Harry Shomer, Shenglai Zeng, Haoyu Han, Yu Wang, Jiliang Tang. \
https://arxiv.org/abs/2503.13804 (2025).

[Empowering GraphRAG with Knowledge Filtering and Integration](https://arxiv.org/abs/2503.13804) \
Kai Guo, Harry Shomer, Shenglai Zeng, Haoyu Han, Yu Wang, Jiliang Tang. \
https://arxiv.org/abs/2503.13804 (2025).

[Personalized Graph-Based Retrieval for Large Language Models](https://arxiv.org/abs/2501.02157) \
Steven Au, Cameron J. Dimacali, Ojasmitha Pedirappagari, Namyong Park, Franck Dernoncourt, Yu Wang, Nikos Kanakaris, Hanieh Deilamsalehy, Ryan A. Rossi, Nesreen K. Ahmed. \
https://arxiv.org/abs/2501.02157 (2025).

[DynaSaur: Large language agents beyond predefined actions](https://arxiv.org/abs/2411.01747)[code](https://github.com/adobe-research/dynasaur) \
Dang Nguyen, Viet Dac Lai, Seunghyun Yoon, Ryan A. Rossi, Handong Zhao, Ruiyi Zhang, Puneet Mathur, Nedim Lipka, Yu Wang, Trung Bui, Franck Dernoncourt, Tianyi Zhou. \
Second Conference on Language Modeling, Montreal, Canada, October 7-9, 2025.

[Towards Trustworthy Knowledge Graph Reasoning: An Uncertainty Aware Perspective](https://arxiv.org/abs/2410.08985) \
Bo Ni, Yu Wang, Lu Cheng, Erik Blasch, Tyler Derr. \
In Proceedings of the 39th AAAI Conference on Artificial Intelligence (AAAI), Philadelphia, PA, February 25-March 4, 2025.

[Topology-aware Retrieval Augmentation for Text Generation](https://dl.acm.org/doi/abs/10.1145/3627673.3679746)\
Yu Wang, Nedim Lipka, Ruiyi Zhang, Alexa Siu, Yuying Zhao, Bo Ni, Xin Wang, Ryan Rossi, Tyler Derr. \
In Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM), Boise, ID, October 21-25, 2024.

[GUI Agents: A Survey](https://arxiv.org/abs/2412.13501) \
Dang Nguyen, Jian Chen, Yu Wang, Gang Wu, Namyong Park, Zhengmian Hu, Hanjia Lyu, Junda Wu, Ryan Aponte, Yu Xia, Xintong Li, Jing Shi, Hongjie Chen, Viet Dac Lai, Zhouhang Xie, Sungchul Kim, Ruiyi Zhang, Tong Yu, Mehrab Tanjim, Nesreen K. Ahmed, Puneet Mathur, Seunghyun Yoon, Lina Yao, Branislav Kveton, Thien Huu Nguyen, Trung Bui, Tianyi Zhou, Ryan A. Rossi, Franck Dernoncourt. \
https://arxiv.org/abs/2412.13501 (2024).

[Knowledge Graph-based Session Recommendation with Session-Adaptive Propagation](https://dl.acm.org/doi/abs/10.1145/3589335.3648324)\
Yu Wang, Amin Javari, Janani Balaji, Walid Shalaby, Tyler Derr, Xiquan Cui. \
Proceedings of the ACM Web Conference (WWW), Singapore, May 13-17, 2024.

[Can One Embedding Fit All? A Multi-Interest Learning Paradigm Towards Improving User Interest Diversity Fairness](https://dl.acm.org/doi/abs/10.1145/3589334.3645662)\
Yuying Zhao, Minghua Xu, Huiyuan Chen, Yuzhong Chen, Yiwei Cai, Rashidul Islam, Yu Wang, Tyler Derr. \
Proceedings of the ACM Web Conference (WWW), Singapore, May 13-17, 2024.

[Knowledge Graph Prompting for Multi-Document Question Answering](https://ojs.aaai.org/index.php/AAAI/article/view/29889)\
Yu Wang, Nedim Lipka, Ryan A. Rossi, Alexa Siu, Ruiyi Zhang, Tyler Derr. \
In Proceedings of the 38th AAAI Conference on Artificial Intelligence (AAAI), Vancouver, Canada, February 20-27, 2024.

[Collaboration-Aware Graph Convolutional Network for Recommender Systems](https://arxiv.org/abs/2207.06221)\
Yu Wang, Yuying Zhao, Yi Zhang, Tyler Derr.\
14th International Conference on Applications of Statistics and Probability in Civil Engineering, ICASP 14, Dublin, Ireland, July 9-13, 2023.


### Resources
[Retrieval-Augmented Generation with Graphs (GraphRAG)](https://arxiv.org/abs/2501.00309v1)\
[paper list](https://github.com/Graph-RAG/GraphRAG/)\
Haoyu Han, Yu Wang, Harry Shomer, Kai Guo, Jiayuan Ding, Yongjia Lei, Mahantesh Halappanavar, Ryan A. Rossi, Subhabrata Mukherjee, Xianfeng Tang, Qi He, Zhigang Hua, Bo Long, Tong Zhao, Neil Shah, Amin Javari, Yinglong Xia, Jiliang Tang. \
https://arxiv.org/abs/2501.00309v1 (2025).

[Towards Trustworthy Retrieval Augmented Generation for Large Language Models: A Survey](https://arxiv.org/abs/2502.06872)\
[paper list](https://github.com/Arstanley/Awesome-Trustworthy-RAG)\
Bo Ni, Zheyuan Liu, Leyao Wang, Yongjia Lei, Yuying Zhao, Xueqi Cheng, Qingkai Zeng, Luna Dong, Yinglong Xia, Krishnaram Kenthapadi, Ryan Rossi, Franck Dernoncourt, Md Mehrab Tanjim, Nesreen Ahmed, Xiaorui Liu, Wenqi Fan, Erik Blasch, Yu Wang, Meng Jiang, Tyler Derr. \
https://arxiv.org/abs/2502.06872 (2025).

### Tutorials
[Retrieval-augmented Generation on Graph-structured Data](https://kindlab-fly.github.io/tutorials/sdm25/)\
Yu Wang, Haoyu Han, Harry Shomer, Kai Guo, Yongjia Lei, Jiayuan Ding, Xianfeng Tang, Qi He, Jiliang Tang.

### Workshops
[Machine Learning on Graphs in the Era of Generative Artificial Intelligence](https://mlgraphworkshop.github.io/)\
Yu Wang, Yu Zhang, Zhichun Guo, Harry Shomer, Haoyu Han, Tyler Derr, Nesreen Ahmed, Mahantesh Halappanavar, Jiliang Tang.

## Acknowledgements
We thank Dr. Erik Blasch, Dr. Xiquan Cui, Dr. Mahantesh Halappanavar, Dr. Krishnaram Kenthapadi, Dr. Jun Li, Dr. Ryan Rossi, and Dr. Yinglong Xia for supporting our collaboration. This work is supported by the National Science Foundation through III 2524379. The views and conclusions contained herein are those of the authors and should not be interpreted as necessarily representing the official policies or endorsements, either expressed or implied, of NSF, AFRL, THD, PNNL, Oracle, Adobe, Meta.

![]({{ site.baseurl }}/images/funding/NSF_logo_animation.gif)

