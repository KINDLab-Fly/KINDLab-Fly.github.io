---
title: "Agentic Reasoning and Decision-making for Structured Drug Design"
layout: textlay
excerpt: "Agentic Reasoning and Decision-making for Structured Drug Design"
sitemap: false
permalink: /projects/agentic-structured-drug-design/
---

# Agentic Reasoning and Decision-making for Structured Drug Design

![]({{ site.url }}{{ site.baseurl }}/images/projects/agentic-drug-design.png){: style="width: 700px; height: auto; display: block; margin: 20px auto;" }

The concept figure illustrates the project workflow: an LLM agent reasons across molecular graph structure, scaffold constraints, protein-binding context, learned property predictors, calculated property feedback, and iterative design loops. Rather than producing a molecule in one step, the agent can plan around a desired scaffold, generate candidates under multiple property constraints, inspect evidence, and revise designs through structured reasoning.

## Project Team

**Team**: Yu Wang, Eugene Douglass, Zhisheng Qi

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

Drug discovery depends on reasoning over multiple structured signals: molecular graphs, scaffold constraints, binding-site geometry, assay evidence, biological context, calculated molecular properties, and candidate trade-offs. This project designs agentic reasoning systems that use those structures as first-class reasoning objects rather than treating drug design as only text generation or black-box molecule sampling.

The demo illustrates a structured reasoning workflow for molecular design. It currently supports specifying a scaffold, sketching a scaffold, and setting multi-constrained property targets. Given these conditions, the system conditionally generates candidate molecules and returns calculated property feedback so users can inspect whether candidates satisfy the intended design constraints. We train LLM agents over more than 10 million molecules so they can reason conditionally over scaffolds and multi-constrained molecular properties. This enables the agent to inspect molecular candidates, connect graph-level and structural evidence, evaluate property trade-offs, compare alternatives, and refine candidate molecules through feedback. The project aims to make drug-design reasoning more transparent, controllable, and scientifically grounded by combining graph-based molecular representations with neural reasoning and domain-guided evaluation.

Key directions include:

- **Scaffold-conditioned generation:** Guide molecular design around desired scaffold structures while preserving chemically meaningful graph patterns.
- **Multi-property constrained reasoning:** Optimize candidates across multiple molecular objectives and constraints rather than a single score.
- **Large-scale agent training:** Train and evaluate LLM agents over more than 10 million molecules to learn reusable reasoning patterns for design, screening, and refinement.
- **Iterative design loops:** Support candidate generation, evaluation, critique, and refinement through multi-step agent workflows.
- **Trustworthy discovery support:** Surface intermediate evidence and decision paths so users can inspect why a candidate is promising or risky.

## Contact

Yu Wang: Yu.Wang6@uga.edu
