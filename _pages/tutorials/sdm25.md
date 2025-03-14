---
title: "SDM25"
layout: textlay
excerpt: "SDM25"
sitemap: false
permalink: /tutorials/SDM25/
---

# Retrieval-augmented Generation on Graph-structured Data
# Tutorial at SIAM International Conference on Data Mining (SDM25)

## Abstract

Retrieval-augmented Generation (RAG), as a powerful technique to enhance downstream task execution by incorporating knowledge from external data sources, has achieved notable success in real-world applications, especially those high-stake social good scenarios, such as healthcare, law, finance, and education. This success has become further unprecedented given the advent of large language models (LLMs) as equipping LLMs with RAG systems (RAGs) significantly enhances the social responsibility and safety of LLMs, including mitigating hallucination, enhancing transparency, enabling dynamic adaptability, reducing privacy risks, and ensuring robustness. However, traditional RAGs are mainly designed for unstructured data, such as text and images, and face significant challenges when facing graph-structured knowledge.

Graph-structured knowledge, like many other data modalities, is ubiquitous across various domains. For example, social graphs reveal homophily among individuals and sequential decision-making steps in planning graphs sometimes adhere to causal logic, and atoms within the same functional groups could exhibit distinct structural properties. This inherent "nodes connected by edges" nature encodes heterogeneous relational knowledge and offers a valuable resource for RAGs. However, pairing RAGs with graph-structured knowledge is challenging. Unlike conventional RAGs where knowledge is stored as image patches or text corpora, graph-structured knowledge takes various forms, such as text in document graphs, triplets/paths in knowledge graphs, images in scene graphs and their combinations in semi-structured databases. Additionally, this knowledge may be distributed across different levels, such as node/edge/subgraph-level, which desires versatile RAG designs such as graph traversal 
in addition to the conventional methods. Moreover, graphs are fundamentally different across different domains, making the ``one-size-fits-all" RAGs nearly impossible and the domain expertise indispensable.

Recognizing the significant efforts in developing RAGs and their potential when coupled with LLMs, yet noting that the current landscape in GraphRAGs remains fragmented with varying concepts, techniques, and datasets, our tutorial aims to make a timely contribution by emphasizing the need to equip RAGs with graph-structured knowledge and develop GraphRAG systems (GraphRAGs). Specifically, our objectives are to 
- **Introduce the foundations of RAGs and graph-structured knowledge**
- **Present representative graph-structured knowledge, tasks, and GraphRAGs across four domains**
- **Discuss crucial challenges for future work**




## Time and Location
Time:  <br>
Location: Edison A, The Westin Alexandria Old Town, Alexandria, Virginia, USA

## Tutorial Outline

<ul>
  <li>
    <b>Introduction and Background</b> (10 min)
    <ul>
      <li> Retrieval-augmented Generation</li>
      <li> Graph-structured Data</li>
      <li> RAG on Graphs</li>
    </ul>
  </li>
  
  <li>
    <b>GraphRAG on Document Graphs</b> (25 min) - Haoyu Han
    <ul>
      <li> TBD </li>
      <li> TBD </li>
      <li> TBD </li>
      <li> Future Directions</li>
    </ul>
  </li>
  
  <li>
    <b>GraphRAG on Knowledge Graphs</b> (25 min) - Harry Shomer
    <ul>
      <li> TBD </li>
      <li> TBD </li>
      <li> TBD </li>
      <li> Future Directions</li>
    </ul>
  </li>
  
  <li>
    <b>Short Break</b> (5 min)
  </li>
  
  <li>
    <b>GraphRAG on Scientific Graphs</b> (25 min) - Kai Guo
    <ul>
      <li> TBD </li>
      <li> TBD </li>
      <li> TBD </li>
      <li> Future Directions</li>
    </ul>
  </li>
  
  <li>
    <b>GraphRAG on Reasoning & Planning Graphs</b> (25 min) - Yongjia Lei
    <ul>
      <li> TBD </li>
      <li> TBD </li>
      <li> TBD </li>
      <li> Future Directions</li>
    </ul>
  </li>

  <li>
    <b>Conclusion</b> (5 min)
  </li>
</ul>



## Slides
Incoming Soon!

## Speakers Bio's

<img src="{{ site.url }}{{ site.baseurl }}/images/Yu.png" class="img-responsive" width="10%" style="float: left; margin-right: 15px; margin-bottom: 10px;" />
<b><a href="https://yuwvandy.github.io/">Yu Wang</a></b> is an incoming Assistant Professor in the Department of Computer Sciences at the University of Oregon. Before joining University of Oregon, he obtained his Ph.D. degree in Computer Science at Vanderbilt University in 2024 under the supervision of Prof. Tyler Derr. His research interests include Graph Data Mining and Data-centric Machine Learning. He received numerous honors including the Best Paper Award in the 2020 Smokey Mountain Data Challenge Competition by ORNL and GLFrontiers Workshop at Neurips'23, Best Doctoral Forum Poster Runner-ups at SDM'24. He actively contributed to the community, both in terms of publishing and serving as PC member/reviewer/organizer such as ICLR, NeurIPS, AAAI, KDD, WWW, CIKM, WSDM, TKDD, TIST. He has contributed to the organization of workshops in WSDM'22/24, and the student travel award chair in CIKM'24.
<br>
<br>

<img src="{{ site.url }}{{ site.baseurl }}/images/Haoyu.png" class="img-responsive" width="10%" style="float: left; margin-right: 15px; margin-bottom: 10px;"/>
<b><a href="https://cse.msu.edu/~hanhaoy1/">Haoyu Han</a></b> is a senior year Ph.D. student at Michigan State University. His research interests include Machine Learning on Graphs and LLMs with Graphs.  Before joining MSU, he completed his M.S. (2021) and B.S. (2018) at USTC. After joining MSU, he has published several works in top conferences (e.g., KDD, ICDM, NeurIPS, ICML, and ICLR). He was the recipient of the KDD’22 and NeurIPS’24 Student Travel Awards. He has contributed to organizing workshops for KDD'23, AAAI'24, and SDM'24.
<br>
<br>
<img src="{{ site.url }}{{ site.baseurl }}/images/Harry.png" class="img-responsive" width="10%" style="float: left; margin-right: 15px; margin-bottom: 10px;" />
<b><a href="https://cse.msu.edu/~shomerha/">Harry Shomer</a></b> is a 5th year Ph.D. student in Computer Science at Michigan State University. His research interests include Machine Learning on Graphs, Trustworthy AI, and AI+Education. Prior to joining MSU, he received his B.S in Computer Science at CUNY -- Brooklyn College (2019). He work has been published at top conferences including NeurIPS, ICLR, KDD, EMNLP, TheWebConf, ACL, and CIKM. He is the recipient of the MSU Engineering Distinguished fellowship, the NRT-IMPACTS fellowship, and the  KDD’24 student travel award.
<br>
<br>
<img src="{{ site.url }}{{ site.baseurl }}/images/Jian.png" class="img-responsive" width="10%" style="float: left; margin-right: 15px; margin-bottom: 10px;" />
<b><a href="https://kaiguo20.github.io/">Kai Guo</a></b> is currently a postdoctoral researcher at Michigan State University. His research interests include Graph Learning and LLMs with Graphs. Before joining MSU, he received his Ph.D. degree from Jilin University in 2024 under the supervision of Prof. Yi Chang. He has published several works in top
conferences including ICML, KDD, and AAAI.
<br>
<br>
<img src="{{ site.url }}{{ site.baseurl }}/images/Yongjia.png" class="img-responsive" width="10%" style="float: left; margin-right: 15px; margin-bottom: 10px;" />
<b><a href="https://yoega.github.io/Yoega.html">Yongjia Lei</a></b> is a 1$^{\text{st}}$ year Ph.D. student in the School of Computer and Data Sciences at the University of Oregon. Her research interests include Knowledge-intensive LLMs and Graph Machine Learning for Social Good Applications. She has several publications in EAAI and ASC. In addition, she has contributed to community services, such as being (sub)-reviewer in KDD, WSDM, AAAI, and LOG.
<br>
<br>
<img src="{{ site.url }}{{ site.baseurl }}/images/Jiayuan.png" class="img-responsive" width="10%" style="float: left; margin-right: 15px; margin-bottom: 10px;" />
<b><a href="https://www.linkedin.com/in/jiayuand/">Jiayuan Ding</a></b> is a Staff Research Scientist responsible for Retrieval Augmented Generation at Hippocratic AI, where its RAG products are serving pharmacies, hospitals, and medical institutions. His research centers on Large Language Models, Retrieval Augmented Generation, Agents, and their applications in life science. His work has been published in top conferences and journals, including NeurIPS, ICLR, ACL, EMNLP, KDD, ICDE, CIKM, ACM TIST, and Genome Biology.
<br>
<br>
<img src="{{ site.url }}{{ site.baseurl }}/images/Xianfeng.png" class="img-responsive" width="10%" style="float: left; margin-right: 15px; margin-bottom: 10px;" />
<b><a href="https://xta.ng/">Xianfeng Tang</a></b> is an Applied Scientist in the Amazon Search Query Understanding team at Amazon. His research is mainly about machine learning, data mining, knowledge graphs, and graph neural networks. He obtained his PhD degree from Pennsylvania State University and his Bachelor's degree from the University of Science and Technology of China. He has published innovative works in top-tier conferences such as ICLR, ICML, NeurIPS, KDD, etc.
<br>
<br>
<img src="{{ site.url }}{{ site.baseurl }}/images/Qi He.png" class="img-responsive" width="10%" style="float: left; margin-right: 15px; margin-bottom: 10px;" />
<b><a href="https://xta.ng/">Qi He</a></b> as Amazon's Director of Applied Science, is a technical leader in AI and its business applications, with a track record of 20 years of experience leading and executing large complex AI projects. He serves as a Steering Committee member of ACM CIKM and an advisory board member of Neurocomputing Journal. He held many editorial and conference chair positions, including Associate Editor of IEEE TKDE and Neurocomputing Journal, General Chair of CIKM 2013, PC Chair of CIKM 2019 and Industry Chair of Web 2024, while also served as a (senior) program committee member of SIGKDD, SIGIR, WWW, CIKM, and WSDM for over a decade. Qi has published over 70 papers and patents with over 7000 citations to date. He received the 2008 ACM SIGKDD Best Application Paper Award and the 2020 ACM WSDM 10-year Test of Time Award. Qi is an IEEE Fellow, ACM Distinguished Member and was featured as the People of ACM in February 2021.
<br>
<br>
<img src="{{ site.url }}{{ site.baseurl }}/images/.png" class="img-responsive" width="10%" style="float: left; margin-right: 15px; margin-bottom: 10px;" />
<b><a href="https://www.cse.msu.edu/~tangjili/">Jiliang Tang</a></b> is a University Foundation Professor in the computer science and engineering department at Michigan State University. His research interests include graph machine learning, trustworthy AI, and their applications in Education and Biology. He authored the first comprehensive book “Deep Learning on Graphs” with Cambridge University Press and developed various well-received open-sourced tools including scikit-feature for feature selection, DeepRobust for trustworthy AI, and DANCE for single-cell analysis. He was the recipient of various career awards (2022 IAPR J. K. AGGARWAL, 2022 SIAM SDM, 2021 IEEE ICDM, 2021 IEEE Big Data Security, 2020 ACM SIGKDD, 2019 NSF), numerous industrial faculty awards, and 8 best paper awards (or runner-ups) including WSDM2018 and KDD2016. He serves as conference organizer (e.g., KDD, SIGIR, WSDM, and SDM) and journal editor (e.g., TKDD, TOIS, and TKDE). He has organized 20+ workshops in top AI conferences such as AI for Education in AAAI20, AAAI21 Spring Symposium on Artificial Intelligence for K-12 Education, DLG-AAAI'21 and DLG-AAAI'23. He has published his research in highly ranked journals and top conference proceedings, which have 38,000 citations with h-index 95 and extensive media coverage.
