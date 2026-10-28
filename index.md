---
layout: home
title: Home
image: /assets/images/prof_pic.webp
show_news: false
---
I am a PhD Candidate at [Mila](https://mila.quebec/en) and [Polytechnique Montréal](https://www.polymtl.ca), supervised by [Prof. Amal Zouaq](https://mila.quebec/en/directory/amal-zouaq) in the [LAMA-WeST Lab](https://labowest.ca). My research focuses on **large language models** applied to the **medical domain**, with a particular interest in **information extraction**, **non-parametric memories** and **agentic workflows**.

Before my PhD, I completed an M.Sc. in Computer Science (NLP) at the [RALI](https://rali.iro.umontreal.ca), Université de Montréal, under the supervision of [Prof. Philippe Langlais](https://www-labs.iro.umontreal.ca/~felipe/brand_new_home/creative-design/public_html/index.php?lg=fr), on evaluation methods for open information extraction. That work led to [BenchIE^FL](https://aclanthology.org/2024.findings-acl.496/), an information extraction benchmark published at ACL 2024, and to general work on **evaluation methodology for information extraction and text generation systems**, which remains a common thread across my research, from structured information extraction to hallucination detection.

Beyond the lab, I have kept one foot in applied AI and industry: as a **Scientist in Residence at [IVADO](https://ivado.ca)** (RemedIA program), where I set up LLM fine-tuning and RAG for an EdTech startup, and as a **speaker in IVADO's AI awareness program**, with talks such as *The ABCs of AI* and *AI, a risk for our democracy?*. I also worked as a **Data Scientist** at Intact Insurance and at Santé Québec, and I was a **teaching assistant for the NLP course at Polytechnique Montréal** in the Fall 2025 semester.

#### News

{% assign news = site.news | sort: 'date' | reverse %}
{% for entry in news limit:3 %}
- <small>{{ entry.date | date_to_string }}</small> — [{{ entry.title }}]({{ entry.url }}) {{ entry.content | strip_html }}
{% endfor %}

#### Contact
fabrice.lamarche _at_ mila.quebec

You can also find me on [Google Scholar](https://scholar.google.com/citations?user=vrGzOI0AAAAJ&hl=en), [GitHub](https://github.com/fbl10) and [LinkedIn](https://www.linkedin.com/in/fabrice-lamarche).
