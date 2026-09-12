---
permalink: /
title: "谈星伟 (Xingwei Tan)"
excerpt: "Research Associate in NLP at the University of Sheffield, working on reasoning in large language models."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Research Associate (post-doctoral researcher) at the [School of Computer Science](https://www.sheffield.ac.uk/cs), University of Sheffield, where I work on **reasoning in large language models**. I completed my PhD at the Department of Computer Science, University of Warwick, supervised by Prof. [Yulan He](https://www.kcl.ac.uk/people/yulan-he) and Dr. [Gabriele Pergola](https://warwick.ac.uk/fac/sci/dcs/people/u1898418/).

I work with Prof. [Nikolaos Aletras](https://sheffield.ac.uk/cs/people/academic/nikos-aletras) and Prof. [Maria Liakata](https://www.qmul.ac.uk/eecs/people/profiles/liakatamaria.html) on the EPSRC project "Addressing Socio-technical Limitations of LLMs for Medical and Social Computing" ([AdSoLve](https://rai.ac.uk/new_projects/addressing-socio-technical-limitations-of-llms-for-medical-and-social-computing-adsolve/)), funded by UKRI via Responsible AI UK as a keystone project.

## Research

My research investigates **the mechanisms underlying reasoning in large language models**: how reasoning behaviour is induced, whether chain-of-thought reflects the computation that actually drives a model's answer, and how far reasoning skills learned in one domain transfer to another. I approach this by combining **behavioural and mechanistic analysis** with **neuro-symbolic methods**.

Three recent threads give a sense of the work. On *inducing* reasoning, [Symbolically-Guided Monte Carlo Process Supervision](https://aclanthology.org/2025.emnlp-main.1624/) (EMNLP 2025) uses symbolic structure to generate reliable process-level reward signals, training on the validity of intermediate steps rather than only the final answer. On *faithfulness*, [Analysing Chain of Thought Dynamics](https://aclanthology.org/2025.emnlp-main.1516/) (EMNLP 2025) asks whether chain-of-thought genuinely guides a model's computation or is reconstructed after the fact. On *transfer*, [Fundamental Reasoning Paradigms](https://doi.org/10.18653/v1/2026.findings-acl.1653) (Findings of ACL 2026) studies which training signals induce reasoning that survives a shift out of domain.

This builds on a broader background in **information extraction and language understanding** (e.g., event
relation extraction, event graph generation, and question answering) and is grounded in applied work with legal and law-enforcement partners, where reasoning failures carry serious consequences. My PhD thesis was *"Understanding Event Relation in Text via Representation Learning and LLM-based Graph Generation"*.

I am happy to collaborate on:

* **Reasoning in LLMs:** logical, mathematical and legal reasoning; process supervision; chain-of-thought faithfulness; generalisation under distribution shift
* **Neuro-symbolic AI:** combining symbolic structure with neural models for verifiable reasoning
* **Evaluation of LLMs:** especially in high-stakes domains such as law
* **Event-centric NLP:** event detection, event relation extraction, temporal and salient event graph generation
* **AI for policing and education:** harmful and abusive language detection, modelling engagement in educational dialogue
* **AI for Science** 

## News

* **Sep 2026** — Two papers accepted to **EMNLP 2026**: *Compliance vs. Sensibility* (Findings) and *An Empirical Study on Preference Tuning Generalization and Diversity Under Domain Shift*.
* **Sep 2026** — *Can Confidence Estimates Decide When Chain-of-Thought Is Necessary for LLMs?* accepted to **Findings of AACL–IJCNLP 2026**.
* **Jul 2026** — *No Shortcuts to Culture*, on Indonesian multi-hop cultural QA, is published in **TACL**.
* **Jul 2026** — *Fundamental Reasoning Paradigms Induce Out-of-Domain Generalization* appears at **Findings of ACL 2026**.
* **2025 – 2026** — Serving as **Area Chair** for ACL Rolling Review (rounds serving EMNLP 2025 and EACL 2026).
* **Nov 2025** — Three papers at **EMNLP 2025**: two in the main conference (process supervision for logical reasoning; chain-of-thought dynamics) and *IntrEx* in Findings.
* **Nov 2025** — Our rapid evidence review of LLM evaluation for legal use cases is published in *AI & SOCIETY*.
* **Apr 2025** — Two papers at **NAACL 2025**: *Cascading Large Language Models for Salient Event Graph Generation* (long) and *SafeSpeech* (system demonstration).
* **2024** — Joined the University of Sheffield as a post-doctoral researcher on the AdSoLve project.

## Selected Publications

See the [full list of publications](/publications/) or my [Google Scholar profile](https://scholar.google.com/citations?user=GAUKDsYAAAAJ&hl=en).

* **Fundamental Reasoning Paradigms Induce Out-of-Domain Generalization in Language Models**<br />
  Mingzi Cao, **Xingwei Tan**, Mahmud Elahi Akhter, Marco Valentino, Maria Liakata, Xi Wang, Nikolaos Aletras<br />
  *Findings of ACL 2026* · [Paper](https://doi.org/10.18653/v1/2026.findings-acl.1653)

* **Compliance vs. Sensibility: On the Reasoning Controllability in Large Language Models**<br />
  **Xingwei Tan**, Marco Valentino, Mahmud Elahi Akhter, Yuxiang Zhou, Maria Liakata, Nikolaos Aletras<br />
  *Findings of EMNLP 2026 (to appear)* · [Paper](https://arxiv.org/abs/2604.27251)

* **Can Confidence Estimates Decide When Chain-of-Thought Is Necessary for LLMs?**<br />
  Samuel Lewis-Lim, **Xingwei Tan**, Zhixue Zhao, Nikolaos Aletras<br />
  *Findings of AACL–IJCNLP 2026 (to appear)* · [Paper](https://arxiv.org/abs/2510.21007)

* **Enhancing Logical Reasoning in Language Models via Symbolically-Guided Monte Carlo Process Supervision**<br />
  **Xingwei Tan**, Marco Valentino, Mahmud Elahi Akhter, Maria Liakata, Nikolaos Aletras<br />
  *EMNLP 2025* · [Paper](https://aclanthology.org/2025.emnlp-main.1624/)

* **Cascading Large Language Models for Salient Event Graph Generation**<br />
  **Xingwei Tan**, Yuxiang Zhou, Gabriele Pergola, Yulan He<br />
  *NAACL 2025* · [Paper](https://aclanthology.org/2025.naacl-long.112/)

* **A Rapid Evidence Review of Evaluation Techniques for Large Language Models in Legal Use Cases**<br />
  Joshua Kelsall, **Xingwei Tan**, et al.<br />
  *AI & SOCIETY, 2025* · [Paper](https://link.springer.com/article/10.1007/s00146-025-02741-9)

## Code & Data

I release code and data for my work. A few artifacts that may be useful on their own:

* **[IntrEx](https://github.com/Xingwei-Tan/IntrEx)** — the first large-scale dataset annotated for
  *interestingness* and *expected interestingness* in teacher–student interactions.
  <span style="white-space: nowrap;">([Findings of EMNLP 2025](https://aclanthology.org/2025.findings-emnlp.1191/))</span>
* **[Symbolic-Guided_MC](https://github.com/Xingwei-Tan/Symbolic-Guided_MC) & [Symbreact-Trace](https://huggingface.co/collections/XingweiT/symbreact-trace)** — symbolically-guided
  Monte Carlo process supervision for training on the validity of intermediate reasoning steps.
  <span style="white-space: nowrap;">([EMNLP 2025](https://aclanthology.org/2025.emnlp-main.1624/))</span>
* **[CALLMSAE](https://github.com/Xingwei-Tan/CALLMSAE)** — a cascading LLM pipeline for generating
  salient event graphs from documents, without reference graphs.
  <span style="white-space: nowrap;">([NAACL 2025](https://aclanthology.org/2025.naacl-long.112/))</span>
* **[Hyper-event-TempRel](https://github.com/Xingwei-Tan/hyper-event-TempRel)** — Poincaré event
  embeddings and a hyperbolic GRU for event temporal relation extraction.
  <span style="white-space: nowrap;">([EMNLP 2021](https://aclanthology.org/2021.emnlp-main.636/))</span>
* **[SafeSpeech](https://aclanthology.org/2025.naacl-demo.31/)** — an interactive tool for analysing
  sexist and abusive language in conversations, built with police partners.
  <span style="white-space: nowrap;">(NAACL 2025 System Demonstration)</span>

More on [GitHub](https://github.com/Xingwei-Tan).


## Talks

* **Nov 2025** · South China University of Technology · School of Software Engineering · Invited by Prof. Yi Cai · "Enhancing Logical Reasoning in Language Models via Symbolically-Guided Monte Carlo Process Supervision"
* **June 2025** · King’s College London · Institute of Psychiatry, Psychology & Neuroscience · Clinical NLP Reading Group · Invited by Dr. Tao Wang · "Understanding Event Relations in Text via Representation Learning and LLM-based Graph Generation"
* **Nov 2024** · The Alan Turing Institute · NLP Special Interest Group · Invited by Dr. Anthony R. Hills · "Understanding Event Relations in Text via Representation Learning and LLM-based Graph Generation"


## Experience & Education

* **Post-doctoral Researcher**, University of Sheffield — 2024 – present<br />
  School of Computer Science. AdSoLve (UKRI / Responsible AI UK keystone project).
* **Research Assistant**, University of Warwick — 2022 – 2024<br />
  Department of Computer Science.
* **PhD in Computer Science**, University of Warwick — 2020 – 2024<br />
  Fully funded by Warwick. Supervisors: Prof. Yulan He and Dr. Gabriele Pergola.
* **MSc in Software Engineering**, South China University of Technology — 2017 – 2020
* **BSc in Logic**, Sun Yat-Sen University — 2013 – 2017

## Contact

I am always glad to hear from people working on reasoning, evaluation, or event understanding. I am open to collaboration, talk, and research visits. Reach me at <Xingwei.Tan@sheffield.ac.uk>.

---

**Short bio** (for talk announcements and chairs). Xingwei Tan is a post-doctoral researcher at the School of Computer Science, University of Sheffield, where he studies the mechanisms underlying reasoning in large language models, combining behavioural and mechanistic analysis with neuro-symbolic methods. He received his PhD from the University of Warwick, where he developed machine learning methods for extracting and analysing event relations using geometric deep learning, Bayesian learning, and large language models. He works on the Responsible AI UK keystone project AdSoLve.
