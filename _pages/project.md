---
title: "KIND Lab - Projects"
layout: gridlay
excerpt: "KIND Lab -- Projects."
sitemap: false
permalink: /project/
---


# Projects

<style>
  .project-list {
    display: grid;
    gap: 32px;
  }

  .project-row {
    display: grid;
    grid-template-columns: minmax(240px, 360px) minmax(0, 1fr);
    gap: 20px;
    align-items: start;
  }

  .project-row img {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 6px;
    box-shadow: 2px 2px 5px #888888;
  }

  .project-row h3 {
    margin-top: 0;
  }

  @media (max-width: 768px) {
    .project-row {
      grid-template-columns: 1fr;
    }

    .project-row img {
      max-width: 420px;
    }
  }
</style>

<div class="project-list">

<div class="project-row">
<a href="https://kindlab-fly.github.io/projects/agentic-structured-drug-design/">
  <img src="{{ site.url }}{{ site.baseurl }}/images/projects/agentic-drug-design.png" alt="Concept figure for agentic intelligence in structured drug design">
</a>
<div>
<h3><a href="https://kindlab-fly.github.io/projects/agentic-structured-drug-design/"><strong>Agentic Intelligence for Structured Drug Design</strong></a></h3>
This project develops agentic intelligence systems for structured drug design. The work studies interactive workflows for specifying design goals, generating candidate molecules, reviewing feedback, and refining alternatives. The goal is to make AI-assisted drug-design workflows more transparent, controllable, and useful for scientific exploration while keeping the public project description focused on high-level capabilities.
</div>
</div>

<div class="project-row">
<a href="https://kindlab-fly.github.io/projects/nsf-III-GraphRAG/">
  <img src="{{ site.url }}{{ site.baseurl }}/images/research/NSF-III-GraphRAG.png" alt="Concept figure for agentic intelligence in structured knowledge retrieval">
</a>
<div>
<h3><a href="https://kindlab-fly.github.io/projects/nsf-III-GraphRAG/"><strong>Agentic Intelligence for Structured Knowledge Retrieval</strong></a></h3>
<p><strong>Team PI</strong>: Yu Wang<br>
<strong>Team Members</strong>: Zhisheng Qi, Yongjia Lei, Utkarsh Sahu</p>
This project develops agentic intelligence systems for structured knowledge retrieval. The work studies interactive workflows for asking questions, retrieving relevant evidence, and inspecting how structured knowledge can support more grounded AI-assisted reasoning. The goal is to make structured retrieval more transparent, useful, and accessible for scientific and decision-making workflows while keeping the public project description focused on high-level capabilities.
</div>
</div>

</div>
