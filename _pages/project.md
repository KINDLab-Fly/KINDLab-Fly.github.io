---
title: "KIND Lab - Projects"
layout: gridlay
excerpt: "KIND Lab -- Projects."
sitemap: false
permalink: /project/
---


# Projects

### [**Agentic Intelligence for Structured Drug Design**](https://kindlab-fly.github.io/projects/agentic-structured-drug-design/)
**Faculty**: Yu Wang, Eugene Douglass<br>
**Student**: Zhisheng Qi<br>
**Live Demo**: [Drug-Design-Agent-Demo](https://drug-design.graphagentintelligence.com/){: target="_blank" rel="noopener noreferrer" }<br>
![]({{ site.url }}{{ site.baseurl }}/images/projects/agentic-drug-design.png){: style="width: 400px; height: auto; float: left; margin: 10px 15px 10px 0px;" }
This project develops agentic intelligence systems for structured drug design. The current demo supports three interactive design modes: specifying a scaffold, sketching a scaffold, and setting multi-constrained molecular property targets. Conditioned on these user inputs, the system generates candidate molecules, calculates property feedback, and lets the agent compare, critique, and refine candidates through multi-step reasoning. We train LLM agents over more than 10 million molecules so they can learn scaffold-conditioned generation, molecular graph constraints, structural biology signals, screening evidence, and property trade-offs. The goal is to move drug-discovery agents beyond one-shot molecule generation toward transparent, controllable, and structure-aware design workflows.

<div style="clear: both; margin-bottom: 30px;"></div>

### [**Agentic Intelligence for Structured Knowledge Retrieval**](https://kindlab-fly.github.io/projects/nsf-III-GraphRAG/)
**Team PI**: Yu Wang<br>
**Team Members**: Zhisheng Qi, Yongjia Lei, Utkarsh Sahu<br>
**Live Demo**: [Graph-Agent-Demo](https://graph-agent.graphagentintelligence.com/){: target="_blank" rel="noopener noreferrer" }<br>
![]({{ site.url }}{{ site.baseurl }}/images/research/NSF-III-GraphRAG.png){: style="width: 400px; height: auto; float: left; margin: 10px 15px 10px 0px;" }
Solutions to real-world problems, such as scientific document question-answering, cybersecurity diagnosis, and e-commerce personalization, can often be improved by augmenting the underlying generative artificial intelligence-based (Gen-AI) systems with retrieved external knowledge. Much of this external knowledge is organized in graph-structured formats that encode unique relational signals. For example, citation links among scientific papers reveal their deep intellectual dependencies across different fields. Recurring co-occurrences among software components and vulnerability reports can reveal latent causal chains triggering security flaws. Online human interactions, such as liking, commenting, or reposting, reflect individual traits and preferences. These project pioneers retrieval techniques that locate the appropriate graph-structured knowledge and infuse it to assist Gen-AI systems with solving downstream problems, closing critical knowledge gaps, and enabling more useful, trustworthy, and diverse predictions, discovery, and decision-making. In personalization, the proposed retrieval techniques could give a social e-commerce platform a holistic view of each customer and support highly personalized recommendations. In cybersecurity, hidden dependencies among vulnerabilities and defenses could be exploited, allowing security operators to trace multi-step attack chains and harden critical systems against emerging threats. In scientific discovery and innovation, the relational knowledge in our proposed graph-level retrieval could facilitate exploration of multifaceted content and provide diverse insights that push existing knowledge boundaries.
