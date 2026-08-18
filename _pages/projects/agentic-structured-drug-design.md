---
title: "Agentic Intelligence for Structured Drug Design"
layout: textlay
excerpt: "Agentic Intelligence for Structured Drug Design"
sitemap: false
permalink: /projects/agentic-structured-drug-design/
---

# Agentic Intelligence for Structured Drug Design

## Project Description

Drug discovery depends on reasoning over multiple structured signals: molecular graphs, scaffold constraints, binding-site geometry, assay evidence, biological context, calculated molecular properties, and candidate trade-offs. This project designs agentic intelligence systems that use those structures as first-class reasoning objects to support controllable and evidence-grounded drug design.

The demo illustrates a structured reasoning workflow for molecular design. It currently supports specifying a scaffold, sketching a scaffold, and setting multi-constrained property targets. Given these conditions, the system conditionally generates candidate molecules and returns calculated property feedback so users can inspect whether candidates satisfy the intended design constraints. We train LLM agents over more than 10 million molecules so they can reason conditionally over scaffolds and multi-constrained molecular properties. This enables the agent to inspect molecular candidates, connect graph-level and structural evidence, evaluate property trade-offs, compare alternatives, and refine candidate molecules through feedback. The project aims to make drug-design reasoning more transparent, controllable, and scientifically grounded by combining graph-based molecular representations with neural reasoning and domain-guided evaluation.

Key directions include:

- **Scaffold-conditioned generation:** Guide molecular design around desired scaffold structures to preserve chemical properties.
- **Multi-Property Constraints:** Optimize candidates across multiple molecular objectives and constraints rather than a single score.
- **Large-scale agent training:** Train and evaluate LLM agents over more than 10 million molecules to learn reusable reasoning patterns for design, screening, and refinement.
- **Iterative design loops:** Support candidate generation, evaluation, critique, and refinement through multi-step agent workflows.

Together, these directions aim to move drug-discovery agents beyond one-shot molecule generation toward interactive design systems that can condition on user-provided chemical structure, reason over multiple properties, and expose intermediate evidence for human inspection.

## Live Demo

Explore the interactive drug-design demo below, or open it in a new tab: [Drug-Design-Agent-Demo](https://drug-design.graphagentintelligence.com/){: target="_blank" rel="noopener noreferrer" }.

<div class="project-demo-embed" style="width: min(1500px, calc(100vw - 32px)); max-width: calc(100vw - 32px); height: 900px; min-height: 780px; margin: 24px 0 34px 50%; transform: translateX(-50%); border: 1px solid #d8dee7; border-radius: 6px; overflow: auto; background: #f8f8f8; box-shadow: 0 8px 24px rgba(15, 23, 42, 0.08);">
  <iframe
    src="https://drug-design.graphagentintelligence.com/"
    title="Drug-Design-Agent-Demo"
    width="100%"
    height="900"
    scrolling="yes"
    loading="lazy"
    allowfullscreen
    style="width: 100%; height: 100%; border: 0; display: block;">
  </iframe>
</div>

## Publications

- **Scaffold-Aware Generative Augmentation and Reranking for Enhanced Virtual Screening**\
Xin Wang, Yu Wang, Yunchao Liu, Jens Meiler, Tyler Derr.\
SIAM International Conference on Data Mining (SDM), 2026.\
[[Paper]](https://arxiv.org/abs/2510.16306)

- **Advancements in Ligand-Based Virtual Screening through the Synergistic Integration of Graph Neural Networks and Expert-Crafted Descriptors**\
Yunchao Liu, Rocco Moretti, Yu Wang, Ha Dong, Bobby Bodenheimer, Tyler Derr, Jens Meiler.\
Journal of Chemical Information and Modeling (JCIM), 2025.

- **WelQrate: Defining the Gold Standard in Small Molecule Drug Discovery Benchmarking**\
Yunchao Liu, Ha Dong, Xin Wang, Rocco Moretti, Yu Wang, Zhaoqian Su, Jiawei Gu, Bobby Bodenheimer, Charles Weaver, Jens Meiler, Tyler Derr.\
Conference on Neural Information Processing Systems (NeurIPS), 2024.\
[[Paper]](https://arxiv.org/abs/2411.09820) [[Code]](http://www.welqrate.org/)

- **Interpretable Chirality-Aware Graph Neural Network for Quantitative Structure-Activity Relationship Modeling in Drug Discovery**\
Yunchao Liu, Yu Wang, Oanh Vu, Rocco Moretti, Bobby Bodenheimer, Jens Meiler, Tyler Derr.\
AAAI Conference on Artificial Intelligence (AAAI), 2023.\
[[Paper]](https://www.biorxiv.org/content/10.1101/2022.08.24.505155v1.abstract) [[Code]](https://github.com/meilerlab/MolKGNN)

- **ChemicalX: A Deep Learning Library for Drug Pair Scoring**\
Benedek Rozemberczki, Charles Tapley Hoyt, Anna Gogleva, Piotr Grabowski, Klas Karis, Andrej Lamov, Andriy Nikolov, Sebastian Nilsson, Michael Ughetto, Yu Wang, Tyler Derr, Benjamin M Gyori.\
ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2022.\
[[Paper]](https://arxiv.org/abs/2202.05240) [[Code]](https://github.com/AstraZeneca/chemicalx)

## Preprints

Project manuscripts and technical reports will be added as they are released.

## Tutorials and Workshops

### Workshops

Related workshops will be added as they are released.

### Tutorials

Related tutorials will be added as they are released.

## Awards and Honors

Project awards and honors will be added as they are released.

## Core Project Team

**Faculty**: [Yu Wang](https://yuwang0103.github.io/), Eugene Douglass

**Student**: [Zhisheng Qi](https://zhishengqi.github.io/)

## Acknowledgements

We thank our academic and domain collaborators for discussions and support on structure-aware drug-design research.

## Contact

Yu Wang: Yu.Wang6@uga.edu
