---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Lecturer (Assistant Professor) in the School of Computer Science and Informatics at Cardiff University, and a member of the [Cardiff NLP](https://www.cardiffnlp.com/) group. Before that, I was a postdoctoral researcher in the same group, working with Prof. [Jose Camacho-Collados](http://josecamachocollados.com/). I received my PhD in Natural Language Processing from the University of Liverpool, advised by Prof. Danushka Bollegala and Dr. Shan Luo, and my MSc in Big Data and High Performance Computing, also from Liverpool.

My research focuses on **responsible AI** — ethics, social bias and fairness in NLP — and on **lexical semantics**. More broadly, I am interested in natural language understanding, including language representation learning, multimodality, commonsense reasoning, multilingual and multicultural NLP, text generation, and the interpretability and analysis of language models.

<span class='anchor' id='news'></span>

# 🔥 News
- *04/01/2026*: &nbsp;🎉 Two papers accepted at the EACL 2026 main conference.
- *20/08/2025*: &nbsp;🎉 Two papers accepted at EMNLP 2025 (one main conference, one Findings).
- *30/07/2025*: &nbsp;🏆 Our paper "BRIGHTER: Bridging the Gap in Human-Annotated Textual Emotion Recognition Datasets for 28 Languages" won the **Best Resource Paper Award** at ACL 2025.
- *26/09/2024*: &nbsp;🎉 One paper accepted at the NeurIPS 2024 Datasets and Benchmarks Track.
- *20/09/2024*: &nbsp;🎉 One paper accepted at the EMNLP 2024 main conference.
- *01/06/2024*: &nbsp;👩‍💻 I started as a Lecturer (Assistant Professor) at Cardiff University.

<details markdown="1">
<summary>Earlier news</summary>

- *20/02/2024*: &nbsp;🎉 One paper accepted at the LREC-COLING 2024 main conference.
- *07/10/2023*: &nbsp;🎉 Three papers accepted at EMNLP 2023 (main conference and Findings).
- *02/08/2023*: &nbsp;👩‍💻 Visiting researcher at the [Users & Information Lab](https://uilab.kr/), KAIST.
- *01/05/2023*: &nbsp;🎉 One paper accepted at the ACL 2023 main conference and two at Findings of ACL 2023.
- *01/02/2023*: &nbsp;👩‍💻 I started as a postdoctoral researcher in Prof. [Jose Camacho-Collados](http://josecamachocollados.com/)'s group at Cardiff University.
- *06/10/2022*: &nbsp;🎉 One paper accepted at Findings of EMNLP 2022.
- *24/02/2022*: &nbsp;🎉 One paper accepted at the ACL 2022 main conference.

</details>

<span class='anchor' id='publications'></span>

# 📝 Selected Publications

For a full list, please see my [Google Scholar](https://scholar.google.com/citations?user=3BdddIMAAAAJ&hl=en) profile. (* equal contribution)

### 2026
- Tianhui Zhang, **Yi Zhou**, Danushka Bollegala. Evaluating the Effect of Retrieval Augmentation on Social Biases. *EACL 2026*.
- Gaifan Zhang, **Yi Zhou**, Danushka Bollegala. CASE — Condition-Aware Sentence Embeddings for Conditional Semantic Textual Similarity Measurement. *EACL 2026*.

### 2025
- Gaifan Zhang, **Yi Zhou**, Danushka Bollegala. Annotating Training Data for Conditional Semantic Textual Similarity Measurement using Large Language Models. *EMNLP 2025*.
- Zirui Li, Siwei Wu, Xingyu Wang, **Yi Zhou**, Yizhi Li, Chenghua Lin. DocMMIR: A Framework for Document Multi-modal Information Retrieval. *Findings of EMNLP 2025*.

### 2024
- Junho Myung\*, Nayeon Lee\*, **Yi Zhou\***, Jiho Jin, Rifki Putri, Dimosthenis Antypas, Hsuvas Borkakoty, Eunsu Kim, Carla Perez-Almendros, Abinew Ali Ayele, Victor Gutierrez Basulto, Yazmin Ibanez-Garcia, Hwaran Lee, Shamsuddeen H. Muhammad, Kiwoong Park, Anar Rzayev, Nina White, Seid Muhie Yimam, Mohammad Taher Pilehvar, Nedjma Ousidhoum, Jose Camacho-Collados, Alice Oh. BLEnD: A Benchmark for LLMs on Everyday Knowledge in Diverse Cultures and Languages. *NeurIPS 2024 Datasets and Benchmarks Track*.
- **Yi Zhou**, Danushka Bollegala, Jose Camacho-Collados. Evaluating Short-Term Temporal Fluctuations of Social Biases in Social Media Data and Masked Language Models. *EMNLP 2024*.
- Gaifan Zhang, **Yi Zhou**, Danushka Bollegala. Evaluating Unsupervised Dimensionality Reduction Methods for Pretrained Sentence Embeddings. *LREC-COLING 2024*.

### 2023
- **Yi Zhou**, Jose Camacho-Collados, Danushka Bollegala. A Predictive Factor Analysis of Social Biases and Task-Performance in Pre-trained Masked Language Models. *EMNLP 2023*.
- Asahi Ushio, **Yi Zhou**, Jose Camacho-Collados. An Efficient Multilingual Language Model Compression through Vocabulary Trimming. *Findings of EMNLP 2023*.
- Xiaohang Tang, **Yi Zhou**, Taichi Aida, Procheta Sen, Danushka Bollegala. Can Word Sense Distribution Detect Semantic Changes of Words? *Findings of EMNLP 2023*.
- Xiaohang Tang, **Yi Zhou**, Danushka Bollegala. [Learning Dynamic Contextualised Word Embeddings via Template-based Temporal Adaptation](https://aclanthology.org/2023.acl-long.520/). *ACL 2023*.
- Saeth Wannasuphoprasit, **Yi Zhou**, Danushka Bollegala. [Solving Cosine Similarity Underestimation between High-Frequency Words by L2 Norm Discounting](https://aclanthology.org/2023.findings-acl.550/). *Findings of ACL 2023*.
- Haochen Luo, **Yi Zhou**, Danushka Bollegala. [Together We Make Sense — Learning Meta-Sense Embeddings](https://aclanthology.org/2023.findings-acl.165/). *Findings of ACL 2023*.

### 2022
- **Yi Zhou**, Danushka Bollegala. [On the Curious Case of ℓ2 Norm of Sense Embeddings](https://aclanthology.org/2022.findings-emnlp.190/). *Findings of EMNLP 2022*.
- **Yi Zhou**, Masahiro Kaneko, Danushka Bollegala. [Sense Embeddings are also Biased — Evaluating Social Biases in Static and Contextualised Sense Embeddings](https://aclanthology.org/2022.acl-long.135/). *ACL 2022*.

<!--
Earlier publications (hidden):
- **Yi Zhou**, Danushka Bollegala. [Learning Sense-Specific Static Embeddings using Contextualised Word Embeddings as a Proxy](https://aclanthology.org/2021.paclic-1.52.pdf). *PACLIC 2021*.
- **Yi Zhou**, Danushka Bollegala. [Predicting the Quality of Translation without an Oracle](https://link.springer.com/chapter/10.1007/978-3-030-66196-0_1). *CCIS*, 2020.
- Guanqun Cao, **Yi Zhou**, Danushka Bollegala, Shan Luo. [Spatio-temporal Attention Model for Tactile Texture Recognition](https://arxiv.org/abs/2008.04442). *IROS 2020*.
- **Yi Zhou**, Danushka Bollegala. [Unsupervised Evaluation of Human Translation Quality](https://www.researchgate.net/publication/336226160_Unsupervised_Evaluation_of_Human_Translation_Quality). *KDIR 2019*.
-->

<span class='anchor' id='experience'></span>

# 👩‍🔬 Experience
- *06/2024 – present*: Lecturer (Assistant Professor), School of Computer Science and Informatics, Cardiff University.
- *02/2023 – 05/2024*: Postdoctoral Research Associate, Cardiff NLP, Cardiff University, with Prof. [Jose Camacho-Collados](http://josecamachocollados.com/).
- *08/2023*: Visiting Researcher, [Users & Information Lab](https://uilab.kr/), KAIST, with Prof. [Alice Oh](https://aliceoh9.github.io/).

<!--
Education (hidden):
- *12/2018 – 06/2023*: PhD in Computer Science (Natural Language Processing), University of Liverpool, UK.
- *09/2017 – 12/2018*: MSc in Big Data & High-Performance Computing (Distinction), University of Liverpool, UK.
- *09/2009 – 06/2013*: BSc in Information Management & Information Systems, Hubei University of Automotive Technology, China.
-->

<span class='anchor' id='service'></span>

# 💻 Professional Service

**Senior roles**
- Senior Area Chair: ACL (2025–), EMNLP (2025–), EACL (2025–), ACL Rolling Review (2025–)
- Area Chair / Action Editor: ACL (2024–), EMNLP (2024–), EACL (2024–), NAACL (2024–), COLING (2024–), ACL Rolling Review (2023–)

**Organising**
- Publication Chair: \*SEM 2026
- Publicity Chair: \*SEM 2024
- Co-organiser: 2nd Cardiff NLP Summer Workshop
- Tutorial Instructor: Learning Dynamic Contextualised Word Embeddings via Template-based Temporal Adaptation (ICWSM 2023 Data Challenge)

**Reviewing**
- Conferences: AAAI (2026), EMNLP (2023–), ACL (2023–), EACL (2022–), ACL Rolling Review (2021–), \*SEM (2023)
- Journals: Natural Language Processing (2024), Information Processing & Management (2023), International Journal of Data Science and Analytics (2023)

<span class='anchor' id='teaching'></span>

# 👩‍🏫 Teaching & Mentoring

**Lecturer, Cardiff University**
- AI Essentials (MSc) (2026–)
- Database Systems (2024–)

**Teaching Assistant, University of Liverpool (2018–2022)**
- MSc: Data Mining and Visualisation; Machine Learning and Bio-inspired Optimisation; Applied Artificial Intelligence
- Undergraduate: App Development; Software Engineering; Object-Oriented Programming; Computer Systems; Mobile Computing; Database Development

**Student mentoring** (University of Liverpool, co-advised with Prof. Danushka Bollegala)
- Xiaohang Tang (BSc, 2022) → PhD student, Virginia Tech
- Gaifan Zhang (BSc, 2022) → MS student, Columbia University
- Saeth Wannasuphoprasit (MSc, 2022) → Data Scientist, Volkswagen Group of America (IECC)
- Haochen Luo (BSc, 2021) → MS student, University of Oxford

<span class='anchor' id='talks'></span>

# 💬 Invited Talks
- *09/2023*: Social Bias in Masked Language Models and Embeddings — Cardiff NLP Seminar, Cardiff University
- *08/2023*: Social Bias in Masked Language Models and Embeddings — NLP/Ethics Seminar, KAIST
- *07/2023*: Social Bias in Masked Language Models and Embeddings — NLP Group, UCL
- *03/2023*: Representation Learning for Word Senses and Evaluation of Their Properties — Cardiff NLP Seminar, Cardiff University
- *06/2021*: Sense Embedding Learning Using Contextualised and Static Word Embeddings — ML Group, University of Liverpool
- *05/2019*: Sense Embedding Learning Using Contextualised and Static Word Embeddings — Research Student Talks, University of Liverpool

Feel free to email me if you'd like me to give a talk at your event or seminar.

<span class='anchor' id='awards'></span>

# 🎖️ Awards
- *2025*: Best Resource Paper Award, ACL 2025
- *2021–2022*: Graduate Association Hong Kong and Tung Scholarship, University of Liverpool
