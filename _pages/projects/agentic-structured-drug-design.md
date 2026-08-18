---
title: "Agentic Reasoning for Structured Drug Design"
layout: textlay
excerpt: "Agentic Reasoning for Structured Drug Design"
sitemap: false
permalink: /projects/agentic-structured-drug-design/
---

# Agentic Reasoning for Structured Drug Design

![]({{ site.url }}{{ site.baseurl }}/images/projects/agentic-drug-design.png){: style="width: 700px; height: auto; display: block; margin: 20px auto;" }

## Live Demo

Explore the interactive drug-design demo below, or open it in a new tab: [Drug-Design-Agent-Demo](https://drug-design.graphagentintelligence.com/){: target="_blank" rel="noopener noreferrer" }.

<div class="project-demo-embed" style="width: min(1500px, calc(100vw - 32px)); max-width: calc(100vw - 32px); height: 900px; min-height: 780px; margin: 24px 0 34px 50%; transform: translateX(-50%); border: 1px solid #d8dee7; border-radius: 6px; overflow: hidden; background: #f8f8f8; box-shadow: 0 8px 24px rgba(15, 23, 42, 0.08);">
  <iframe
    src="https://drug-design.graphagentintelligence.com/"
    title="Drug-Design-Agent-Demo"
    width="100%"
    height="900"
    loading="lazy"
    allowfullscreen
    style="width: 100%; height: 100%; border: 0; display: block;">
  </iframe>
</div>

## Project Description

Drug discovery depends on reasoning over multiple structured signals: molecular graphs, scaffold constraints, binding-site geometry, assay evidence, biological context, and candidate trade-offs. This project studies how agentic AI systems can use those structures as first-class reasoning objects rather than treating drug design as only text generation or black-box molecule sampling.

The demo illustrates a structured reasoning workflow for molecular design. An agent can inspect molecular candidates, connect graph-level and structural evidence, evaluate design constraints, compare alternatives, and refine candidate molecules through feedback. The project aims to make drug-design reasoning more transparent, controllable, and scientifically grounded by combining graph-based molecular representations with neural reasoning and domain-guided evaluation.

Key directions include:

- **Structured molecular reasoning:** Represent molecules, scaffolds, and interactions as structured objects for agent planning and evidence tracking.
- **Iterative design loops:** Support candidate generation, evaluation, critique, and refinement through multi-step agent workflows.
- **Trustworthy discovery support:** Surface intermediate evidence and decision paths so users can inspect why a candidate is promising or risky.

## Contact

Yu Wang: Yu.Wang6@uga.edu
