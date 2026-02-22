---
title: "WSDM26"
layout: textlay
excerpt: "WSDM26"
sitemap: false
permalink: /tutorials/wsdm26/
---

## Rigorizing Retrieval-augmented Generation with Structured Knowledge
## Tutorial at the ACM International Conference on Web Search and Data Mining (WSDM'26)

### Abstract

Retrieving external knowledge to Augment Generations of downstream task solutions (RAGs) has become a standard practice in powering knowledge-intensive applications. However, real-world knowledge often manifests in heterogeneous yet distinctive structures (e.g., tabular schemas, social networks, and document trees), the effective modeling of which demands specialized modeling, practical engineering, and domain expertise. Meanwhile, adopting RAGs in high-stakes scenarios underscores rigorous safety considerations. Despite the importance of this structural perspective, the current landscape remains fragmented. Moreover, few approaches adequately consider how structured knowledge shapes RAG's safety. Against this backdrop, our tutorial offers a structural perspective on RAGs. We begin by overviewing structured RAGs across their full lifecycle, highlighting their canonical designs. We then examine how design principles can be specialized for different knowledge structures, showcasing their unique applications and security attack/defense strategies. Specifically, our objectives are to:
- **Introduce the background of RAG and structured knowledge, including their safety concerns in real-world applications**
- **Present a unified perspective on RAG architectures specialized for document, social network, table, and citation network structures**
- **Discuss key security risks in structured RAGs, including knowledge poisoning ant extraction, inference, along with their threat models and defenses**


### Time and Location
Time: Feb 22<br>
Location: Boise Centre Room 110AB, Boise, Idaho, USA

### Tutorial Outline

<ul>
  <li>
    <b>Background and Overview</b> (15 min) - Yu Wang
    <ul>
      <li>Retrieval-augmented Generation</li>
      <li>Structured Knowledge and Applications: Social Network, Table Schema, Documents, and Citation Network</li>
      <li>Security Issues of RAGs and their Structured Variants</li>
    </ul>
  </li>

  <li>
    <b>Structured RAG Workflow</b> (25 min) - Yu Wang
    <ul>
      <li>Standard Workflow</li>
      <li>Structural Variants</li>
    </ul>
  </li>

  <li>
    <b>Short Break</b> (5 min)
  </li>

  <li>
    <b>Document Structured RAGs</b> (40 min) - Yongjia Lei
    <ul>
      <li>Document Tasks and Structured Knowledge (10 min)</li>
      <li>Document Structured RAGs (20 min)</li>
      <li>Future Directions and Q&A (10 min)</li>
    </ul>
  </li>

  <li>
    <b>Social Network Structured RAGs</b> (40 min) - Utkarsh
    <ul>
      <li>Social Network Tasks and Structured Knowledge (10 min)</li>
      <li>Social Network Structured RAGs (20 min)</li>
      <li>Future Directions and Q&A (10 min)</li>
    </ul>
  </li>

  <li>
    <b>Short Break</b> (5 min)
  </li>

  <li>
    <b>Table Structured RAGs</b> (40 min) - Haoyu Han
    <ul>
      <li>Table Tasks and Structured Knowledge (10 min)</li>
      <li>Table Structured RAGs (20 min)</li>
      <li>Future Directions and Q&A (10 min)</li>
    </ul>
  </li>

  <li>
    <b>Citation Network Structured RAGs</b> (40 min) - Yu Zhang
    <ul>
      <li>Citation Network Tasks and Structured Knowledge (10 min)</li>
      <li>Citation Network Structured RAGs (20 min)</li>
      <li>Future Directions and Q&A (10 min)</li>
    </ul>
  </li>

  <li>
    <b>Conclusion of Part 1</b> (10 min) - Yu Wang
  </li>

  <li>
    <b>Long Break</b> (15 min)
  </li>

  <li>
    <b>Democratizing Structured RAGs</b> (15 min) - Zhisheng Qi
    <ul>
      <li>Background and Motivation</li>
      <li>Risk Overview of RAG Workflow</li>
    </ul>
  </li>

  <li>
    <b>Knowledge Integrity Risk on RAGs</b> (25 min) - Zhisheng Qi
    <ul>
      <li>Background and Motivation</li>
      <li>Attack and Defense Method</li>
      <li>Evaluation Protocol</li>
    </ul>
  </li>

  <li>
    <b>Knowledge Inference Risk on RAGs</b> (25 min) - Zhisheng Qi
    <ul>
      <li>Background and Motivation</li>
      <li>Attack and Defense Method</li>
      <li>Evaluation Protocol</li>
    </ul>
  </li>

  <li>
    <b>Knowledge Extraction Risk on RAGs</b> (25 min) - Zhisheng Qi
    <ul>
      <li>Background and Motivation</li>
      <li>Attack and Defense Method</li>
      <li>Evaluation Protocol</li>
    </ul>
  </li>

  <li>
    <b>Knowledge Profiling Risk on RAGs</b> (25 min) - Zhisheng Qi
    <ul>
      <li>Background and Motivation</li>
      <li>Attack and Defense Method</li>
      <li>Evaluation Protocol</li>
    </ul>
  </li>

  <li>
    <b>Conclusion of Part 2</b> (10 min) - Zhisheng Qi
  </li>
</ul>



### Slides
Coming soon.

<!-- Uncomment when slides are available:
Download <a href="https://KINDLab-Fly.github.io/_pages/WSDM26-StructuredRAG-tutorial.pdf"> PDF Link </a>

<div style="display: flex; justify-content: center;">
  <embed src="{{ site.url }}{{ site.baseurl }}/_pages/WSDM26-StructuredRAG-tutorial.pdf" width="700px" height="500px" />
</div>
-->

### Speakers Bio

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Yu Wang.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://yuwvandy.github.io/">Yu Wang</a></b> is an Assistant Professor in the School of Computer and Data Sciences at the University of Oregon. His research interests include Graph Machine Learning, LLMs, Information Retrieval, and Data-centric AI for social good. He received the Best Paper Award in the 2020 Smokey Mountain Data Challenge Competition by ORNL and GLFrontiers Workshop at Neurips'23, and Best Doctoral Forum Poster Runner-ups at SDM'24. He actively contributed to the community, both in publishing and serving as a PC member/reviewer/organizer, such as ICLR, NeurIPS, AAAI, KDD, WWW, CIKM, WSDM, TKDD, and TIST. He has contributed to organizing workshops in WSDM'22/24 and KDD'25 and served as the student travel award chair in CIKM'24.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/Zhisheng.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://zhishengqi.github.io/">Zhisheng Qi</a></b> is a Ph.D. student in the School of Computer and Data Sciences at the University of Oregon. His research interests include Retrieval-augmented Generation, Structured Knowledge, and Security of AI systems. He has contributed to research published in top venues and is actively involved in community services.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Yongjia Lei.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://yoega.github.io/Yoega.html">Yongjia Lei</a></b> is a Ph.D. student in the School of Computer and Data Sciences at the University of Oregon. Her research interests include Knowledge-intensive LLMs and Graph Machine Learning for Social Good Applications. She has several publications in top venues including EAAI and ASC. She has also contributed to community services, serving as a reviewer in KDD, WSDM, AAAI, and LOG. She was a recipient of the SDM'25 student travel award.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Haoyu Han.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://cse.msu.edu/~hanhaoy1/">Haoyu Han</a></b> is a Ph.D. student at Michigan State University. His research interests include Machine Learning on Graphs and LLMs with Graphs. Before joining MSU, he completed his M.S. (2021) and B.S. (2018) at USTC. He has published several works in top conferences (e.g., KDD, ICDM, NeurIPS, ICML, and ICLR). He was the recipient of the KDD'22 and NeurIPS'24 Student Travel Awards. He has contributed to organizing workshops for KDD'23, AAAI'24, and SDM'24.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/Utkarsh.png" class="bio-img" />
  <div class="bio-text">
<b>Utkarsh</b> is a Ph.D. student in the School of Computer and Data Sciences at the University of Oregon. His research interests include Social Network Analysis and Retrieval-augmented Generation.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Harry Shomer.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://cse.msu.edu/~shomerha/">Harry Shomer</a></b> is an Assistant Professor at the University of Texas at Arlington. He received his Ph.D. from Michigan State University. His research interests include Machine Learning on Graphs, Trustworthy AI, and AI in education. Before joining MSU, he received his B.S. in Computer Science from CUNY Brooklyn College (2019). His work has been published at top conferences including NeurIPS, ICLR, KDD, EMNLP, TheWebConf, ACL, and CIKM. He is the recipient of the MSU Engineering Distinguished fellowship, the NRT-IMPACTS fellowship, and the KDD'24 student travel award.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Kaize.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://kaize0409.github.io/">Kaize Ding</a></b> is an Assistant Professor in the Department of Statistics and Data Science at Northwestern University. Before joining Northwestern, he obtained his Ph.D. degree in Computer Science at Arizona State University in 2023 under the supervision of Prof. Huan Liu. His research interests are generally in data mining, machine learning, and natural language processing, with a particular focus on Graph Machine Learning, data-efficient learning, and reliable AI. His work has been published in top-tier conferences and journals (e.g., AAAI, EMNLP, IJCAI, KDD, NeurIPS, TheWebConf, and TNNLS), and has been recognized with several prestigious awards, including the AAAI New Faculty Highlights, SDM Best Posters Award, and Best Paper Award at the Trustworthy Learning on Graphs workshop.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Ryan.png" class="bio-img" />
  <div class="bio-text">
<b><a href="http://ryanrossi.com/">Ryan Rossi</a></b> is a Senior Research Scientist at Adobe Research. His research includes machine learning and spans theory, algorithms, and applications of large complex graph data. He has authored over 100 papers published in top-tier conferences and journals such as NeurIPS, ICML, AAAI, KDD, IJCAI, ICLR, COLT, WWW, WSDM, and JMLR. Before joining Adobe Research, he worked at many industrial, government, and academic research labs including Palo Alto Research Center (Xerox PARC), Lawrence Livermore National Laboratory, and University of Massachusetts Amherst. He earned his Ph.D./M.S. in Computer Science at Purdue University. He brings substantial experience in leveraging social network-structured signals for personalization and applying knowledge graphs to automate document understanding.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Yu Zhang.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://yuzhangbit.github.io/">Yu Zhang</a></b> is an Assistant Professor at Texas A&M University. His research focuses on structure-enhanced text mining for science, including citation network analysis, scientific document understanding, and knowledge discovery. He received his Ph.D. from the University of Illinois at Urbana-Champaign. His work has been published in top-tier conferences and journals including KDD, WWW, and EMNLP.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Hui Liu.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://liuhui.cse.msu.edu/">Hui Liu</a></b> is an Assistant Professor at Michigan State University. His research interests include text mining, knowledge graphs, and information retrieval. He has contributed extensive expertise in knowledge intelligence and has a strong publication record in top-tier conferences and journals.
  </div>
</div>
