---
title: "WSDM26"
layout: textlay
excerpt: "WSDM26"
sitemap: false
permalink: /tutorials/wsdm26/
---

### Rigorizing Retrieval-augmented Generation with Structured Knowledge
### Tutorial at ACM International Conference on Web Search and Data Mining

#### Abstract

Retrieving external knowledge to Augment Generations of downstream task solutions (RAGs) has become a standard practice in powering knowledge-intensive applications. However, real-world knowledge often manifests in heterogeneous yet distinctive structures (e.g., tabular schemas, social networks, and document trees), the effective modeling of which demands specialized modeling, practical engineering, and domain expertise. Meanwhile, adopting RAGs in high-stakes scenarios underscores rigorous safety and privacy considerations. Despite the importance of this structural perspective, the current landscape remains fragmented across different knowledge structures. Moreover, few approaches adequately consider how structured knowledge shapes RAG's safety. Against this backdrop, our tutorial offers a structural perspective on RAGs. We begin by overviewing structured RAGs across their full lifecycle, highlighting their canonical designs. We then examine how design principles can be specialized for different knowledge structures, showcasing their unique applications and security attack/defense strategies. Specifically, our objectives are to:
- **Motivation and Application RAG, structured knowledge, and safety/privacy concerns.**
- **Unified perspective on RAG and specialization in document, social network, table, and citation literature networks**
- **Discuss key security risks in structured RAGs, including knowledge poisoning and extraction attacks**


### Time and Location
Time: Feburary 22<br>
Location: Boise Centre Room 110AB, Boise, Idaho, USA

### Tutorial Outline

<ul>
  <li>
    <b>Background and Overview</b> (9:00-9:30 am) - Yu Wang
    <ul>
      <li>Retrieval-augmented Generation</li>
      <li>Structured Knowledge and Applications: Document, Table, Personalization, Social Network, Scientific Literature, Knowledge Graph</li>
      <li>Security Issues of RAGs and their Structured Variants</li>
    </ul>
  </li>

  <li>
    <b>Document/Table Structured RAGs</b> (9:30-10:00 am) - Haoyu Han
    <ul>
      <li>Document/Table Tasks and Structured Knowledge</li>
      <li>Document Structured RAGs</li>
      <li>Future Directions and Q&A</li>
    </ul>
  </li>

  <li>
    <b>Personalization & Social Structured RAGs</b> (10:00-10:30 am) - Utkarsh Sahu
    <ul>
      <li>Personalization and Social Network Tasks and Structured Knowledge</li>
      <li>Personalization/Social Structured RAGs</li>
      <li>Future Directions and Q&A</li>
    </ul>
  </li>

  <li>
    <b>Coffee Break</b> (10:30-11:00am)
  </li>

  <li>
    <b>Scientific Literature RAGs</b> (11:00-11:30 am) - Yu Zhang
    <ul>
      <li>Scientific Literature Tasks and Structured Knowledge</li>
      <li>Scientific Literature RAGs</li>
      <li>Future Directions and Q&A</li>
    </ul>
  </li>

  <li>
    <b>Knowledge Graph RAGs</b> (11:30 am - 12:00 pm) - Harry Shomer
    <ul>
      <li>Knowledge Graph Tasks and Structured Knowledge</li>
      <li>Knowledge Graph Structured RAGs</li>
      <li>Future Directions and Q&A</li>
    </ul>
  </li>

  <li>
    <b>Security and Privacy of Structured RAGs</b> (12:00 pm - 12:30 pm) - Zhisheng Qi
    <ul>
      <li>Knowledge Poisoning Attacks</li>
      <li>Knowledge Extraction Attacks</li>
    </ul>
  </li>

  <li>
    <b>Conclusion and Future Work</b> (12:30 - 12:40 pm) - Yu Wang
  </li>
</ul>



### Slides
You can download PDF version of our slides or see them embedded below.
Download <a href="https://KINDLab-Fly.github.io/_pages/WSDM26-RAG-Structure.pdf"> PDF Link </a>

<div style="display: flex; justify-content: center;">
  <embed src="{{ site.url }}{{ site.baseurl }}/_pages/WSDM26-RAG-Structure.pdf" width="700px" height="500px" />
</div>


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
<b><a href="https://zhishengqi.github.io/">Zhisheng Qi</a></b> is a Ph.D. student in the School of Computer and Data Sciences at the University of Oregon. His research interests include Retrieval-augmented Generation, Agentic Reasoning and Planning, and Security of AI Agent.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Haoyu Han.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://cse.msu.edu/~hanhaoy1/">Haoyu Han</a></b> is a Ph.D. candidate at Michigan State University. His research interests include Machine Learning on Graphs and LLMs with Graphs. Before joining MSU, he completed his M.S. (2021) and B.S. (2018) at USTC. He has published several works in top conferences (e.g., KDD, ICDM, NeurIPS, ICML, and ICLR). He was the recipient of the KDD'22 and NeurIPS'24 Student Travel Awards. He has contributed to organizing workshops for KDD'23, AAAI'24, and SDM'24.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/Utkarsh.png" class="bio-img" />
  <div class="bio-text">
<b>Utkarsh Sahu</b> is a Ph.D. student in the School of Computer and Data Sciences at the University of Oregon. His research interests include Multi-Modal Learning, Social Network, Personalization.
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
  <img src="{{ site.url }}{{ site.baseurl }}/images/Yu Zhang.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://yuzhangbit.github.io/">Yu Zhang</a></b> is an Assistant Professor at Texas A&M University. His research focuses on structure-enhanced text mining for science, including citation network analysis, scientific document understanding, and knowledge discovery. He received his Ph.D. from the University of Illinois at Urbana-Champaign. His work has been published in top-tier conferences and journals including KDD, WWW, and EMNLP.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Ryan.png" class="bio-img" />
  <div class="bio-text">
<b><a href="http://ryanrossi.com/">Ryan Rossi</a></b> is a Senior Research Scientist at Adobe Research. His research includes machine learning and spans theory, algorithms, and applications of large complex graph data. He has authored over 100 papers published in top-tier conferences and journals such as NeurIPS, ICML, AAAI, KDD, IJCAI, ICLR, COLT, WWW, WSDM, and JMLR. Before joining Adobe Research, he worked at many industrial, government, and academic research labs including Palo Alto Research Center (Xerox PARC), Lawrence Livermore National Laboratory, and University of Massachusetts Amherst. He earned his Ph.D./M.S. in Computer Science at Purdue University. He brings substantial experience in leveraging social network-structured signals for personalization and applying knowledge graphs to automate document understanding.
  </div>
</div>

<div class="speaker-bio">
  <img src="{{ site.url }}{{ site.baseurl }}/images/hui liu.png" class="bio-img" />
  <div class="bio-text">
<b><a href="https://liuhui.cse.msu.edu/">Hui Liu</a></b> is an Assistant Professor at Michigan State University. Her research interests include trustworthy AI, knowledge graph learning, and information retrieval. She has contributed extensive expertise in knowledge intelligence and has a strong publication record in top-tier conferences and journals.
  </div>
</div>
