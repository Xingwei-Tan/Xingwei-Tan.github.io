---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/cv.pdf" class="btn btn--info">Download CV (PDF)</a>

Research Interests
======
My research investigates the mechanisms underlying reasoning in large language models: how reasoning
behaviour is induced, whether chain-of-thought reflects the computation that actually drives a model's
answer, and how far reasoning skills learned in one domain transfer to another. I approach this by
combining behavioural and mechanistic analysis with neuro-symbolic methods.

This builds on a broader background in information extraction and language understanding (e.g., event
relation extraction, event graph generation, and question answering) and is grounded in applied work
with legal and law-enforcement partners, where reasoning failures carry serious consequences.

*Keywords:* Reasoning in LLMs; Chain-of-thought Faithfulness; Neuro-Symbolic AI;
Textual Event Understanding; Evaluation of LLMs.

Employment
======
* **Post-doctoral Researcher**, University of Sheffield, School of Computer Science, 2024 – present
* **Research Assistant**, University of Warwick, Department of Computer Science, 2022 – 2024
* **Graduate Teaching Assistant**, University of Warwick, Department of Computer Science, 2020 – 2024

Education
======
* **Ph.D. in Computer Science**, University of Warwick, 2020 – 2024<br />
  Fully funded by Warwick. Supervisors: Prof. Yulan He and Dr. Gabriele Pergola.<br />
  Thesis: *Understanding Event Relation in Text via Representation Learning and LLM-based Graph Generation*
* **M.Sc. in Software Engineering**, South China University of Technology, Guangzhou, China, 2017 – 2020<br />
  GPA 3.69/4.00. Thesis: *A Study of Aspect Embedding and Conflict Sentiment Recognition on Aspect-Based Sentiment Analysis*
* **B.Sc. in Logic**, Sun Yat-Sen University, Guangzhou, China, 2013 – 2017<br />
  GPA 3.7/4.00. Thesis: *An Aspect-Based Sentiment Analysis System for Online Car Reviews*

Research Projects and Funding
======
* **Addressing Socio-technical Limitations of LLMs for Medical and Social Computing ([AdSoLve](https://rai.ac.uk/new_projects/addressing-socio-technical-limitations-of-llms-for-medical-and-social-computing-adsolve/))**, 2024 – present<br />
  Funded by UKRI via [Responsible AI UK](https://rai.ac.uk/research/keystone-projects/) as a keystone project. Role: post-doctoral researcher.<br />
  Research on LLMs and complex reasoning (logical and legal), developing neuro-symbolic methods for
  real-world problems. Engage directly with law firms to build an evaluation platform that reflects
  practitioner requirements.
* **NLP to Detect Threatening and Abusive Language Toward Victims**, 2023 – 2024<br />
  Funded by the OPCSA Police STAR Fund. Role: lead engineer (team of 3).<br />
  Built a platform helping police gather evidence from victims' devices, analysing text conversations
  with LLMs and providing in-depth, interactive feedback. Generalised and published as a system
  demonstration at NAACL 2025.
* **An Event-Centric Dialogue System for Second Language Learners**, 2022 – 2023<br />
  Funded by the Warwick RDF Science Development Award.<br />
  Built an annotation platform and curated *[IntrEx](https://huggingface.co/collections/XingweiT/intrex)*, the first large-scale dataset annotated for
  interestingness and expected interestingness in teacher–student interactions.

Teaching and Supervision
======
* **Guest Lecturer**, University of Sheffield — *Natural Language Processing*, 2024 – present<br />
  Lectures delivered: Neural Sequence-to-Sequence Models for Machine Translation; In-Context Learning
  and Retrieval Augmented Generation.
* **Teaching Assistant**, University of Warwick, Department of Computer Science, 2020 – 2024<br />
  *Natural Language Processing* (M.Sc., 2020–2024); *Logic and Verification* (B.Sc., 2020–2023);
  *Formal Systems Development* (M.Sc., 2021–2022).<br />
  Duties: delivering seminars and lectures, advising laboratory experiments, and marking.
* **Doctoral supervision** — co-supervised 6 Ph.D. students, resulting in 5 peer-reviewed publications.

Academic Service
======
* **Area Chair**, ACL Rolling Review (ACL ARR), 2025 – 2026 — rounds serving *EMNLP 2025* and *EACL 2026*.
* **Reviewer**, *IEEE Transactions on Audio, Speech and Language Processing*.
* **Reviewer**, ACL Rolling Review (ACL ARR), 2023 – 2026 — rounds serving *NAACL 2024*, *ACL 2024*, *ACL 2026*, *EMNLP 2026*.
* **Reviewer**, *EMNLP* (2023) and *EACL*.
* **Programme Committee**, 4th Workshop on Mathematical Natural Language Processing (MathNLP) at EMNLP 2026.
* **Programme Committee**, 3rd Workshop on Mathematical Natural Language Processing (MathNLP) at EMNLP 2025.
* **Organiser**, NLP seminar series, University of Sheffield, 2024 – present.
* **Mentor** for 2 Student Research Workshop papers at EACL 2025.

Publications
======
{% assign conf = site.publications | where: "category", "conferences" | sort: "date" | reverse %}
{% assign jour = site.publications | where: "category", "manuscripts" | sort: "date" | reverse %}

Conference Proceedings
------
<ul>
{% for post in conf %}
  <li>{{ post.citation | markdownify | remove: '<p>' | remove: '</p>' }},
  {% if post.paperurl %}<a href="{{ post.paperurl }}">{{ post.title }}</a>{% else %}{{ post.title }}{% endif %}.
  <i>{{ post.venue }}</i>, {{ post.date | date: "%Y" }}.</li>
{% endfor %}
</ul>

Journal Articles
------
<ul>
{% for post in jour %}
  <li>{{ post.citation | markdownify | remove: '<p>' | remove: '</p>' }},
  {% if post.paperurl %}<a href="{{ post.paperurl }}">{{ post.title }}</a>{% else %}{{ post.title }}{% endif %}.
  <i>{{ post.venue }}</i>, {{ post.date | date: "%Y" }}.</li>
{% endfor %}
</ul>

References
======
Available on request.
