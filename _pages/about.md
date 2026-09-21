---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year Ph.D. candidate in the HKUST NLP Group at the Hong Kong University of Science and Technology (HKUST), where I am supervised by Professor Junxian He, who also advised me during my undergraduate studies at Shanghai Jiao Tong University. My research focuses on natural language processing and machine learning, with particular interests in LLM reasoning and reinforcement learning, hallucination in vision-language models (VLM), and LLM truthfulness and interpretability.

Academic Background
======
- **Ph.D. in Computer Science (2024-Present)**, Hong Kong University of Science and Technology (HKUST). Member of the HKUST NLP Group, supervised by Professor Junxian He.
- **B.Eng. (2020-2024)**, Shanghai Jiao Tong University (SJTU). Recipient of the Zhiyuan Honor Scholarship.

Research Experience
======
- **Research Intern**, MINIMAX (February 2025 - Present)
- **Research Intern**, Tencent WXG (June 2024 - September 2024). Advised by Zifei Shan.
- **Research Intern**, Shanghai AI Lab (June 2023 - December 2023). Advised by Prof. Yu Cheng.

Publications
======
{% include base_path %}

{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h3>{{ category[1].title }}</h3>
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

Skills
======
- Natural Language Processing
- Machine Learning
- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

Contact
======
- E-mail: jliugi@connect.ust.hk
- GitHub: https://github.com/Vicent0205
- Google Scholar: https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate
- X (Twitter): https://x.com/junteng88716710
