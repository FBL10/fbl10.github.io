---
layout: home
title: Home
image: /assets/images/prof_pic.webp
show_news: false
---
I am a PhD Candidate at [Mila](https://mila.quebec/en) and [Polytechnique Montréal](https://www.polymtl.ca), supervised by [Prof. Amal Zouaq](https://mila.quebec/en/directory/amal-zouaq) in the [LAMA-WeST Lab](https://labowest.ca). My research focuses on **large language models** applied to the **medical domain**, with a particular interest in **information extraction**, **non-parametric memories** and **agentic workflows**.

Before my PhD, I completed an M.Sc. in Computer Science (NLP) at the [RALI](https://rali.iro.umontreal.ca), Université de Montréal, under the supervision of [Prof. Philippe Langlais](https://www-labs.iro.umontreal.ca/~felipe/brand_new_home/creative-design/public_html/index.php?lg=fr), on evaluation methods for open information extraction. That work led to [BenchIE^FL](/projects/benchiefl/), an information extraction benchmark published at ACL 2024, and to general work on **evaluation methodology for information extraction and text generation systems**, which remains a common thread across my research, from structured information extraction to hallucination detection.

#### Professional experience

- **Scientist in Residence at [IVADO](https://ivado.ca)** (2023 – 2025), within the RemedIA AI-consulting program: AI specialist for an EdTech startup, where I set up LLM fine-tuning and RAG for tutoring systems.
- **Speaker for IVADO** (2025 – 2026) in its AI awareness program towards democratizing the technology and community, giving talks such as *The ABCs of AI* and *AI, a risk for our democracy?*
- **Data Scientist at [Intact Insurance](https://www.intact.ca)** (2024 – 2025): redefined the evaluation process for market value prediction, plus performance analysis and model maintenance.
- **AI Analyst for the health network of Québec, CIUSSS du Centre-Sud-de-l'Île-de-Montréal** (2021 – 2023): developed an XGBoost model for predicting hospital stay duration, and strategic data analysis and visualization.

#### News

{% assign news = site.news | sort: 'date' | reverse %}
{% for entry in news limit:3 %}
- <small>{{ entry.date | date_to_string }}</small> — [{{ entry.title }}]({{ entry.url }}) {{ entry.content | strip_html }}
{% endfor %}

#### Contact
fabrice.lamarche _at_ mila.quebec

You can also find me on [Google Scholar](https://scholar.google.com/citations?user=vrGzOI0AAAAJ&hl=en), [GitHub](https://github.com/fbl10) and [LinkedIn](https://www.linkedin.com/in/fabrice-lamarche).
