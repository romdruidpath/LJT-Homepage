---
permalink: /
title: "About me"
excerpt: "About Junteng Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year Ph.D. candidate in the [HKUST NLP Group](https://hkust-nlp.github.io/) at the Hong Kong University of Science and Technology (HKUST), advised by Prof. [Junxian He](https://www.cse.ust.hk/~jhexian/). I received my Bachelor of Engineering degree from Shanghai Jiao Tong University (SJTU) in June 2024.

My research focuses on **natural language processing** and **machine learning**, with particular interests in:

- **LLM Reasoning and Reinforcement Learning** &mdash; synthesizing verifiable reasoning data at scale, training paradigms, and reinforcement-learning-based optimization of large language models.
- **Hallucination in Vision-Language Models (VLMs)** &mdash; understanding and mitigating hallucination in multimodal models, with a focus on chart understanding.
- **LLM Truthfulness and Interpretability** &mdash; investigating the inner mechanisms underlying LLM truthfulness via interpretability methods, and developing reliable approaches to detect and correct untruthful outputs.

I have also held research internships at MINIMAX (2025&ndash;present), Tencent WXG (2024), and Shanghai AI Lab (2023), and I was a co-author of [C-Eval](https://cevalbenchmark.com/), a multi-level multi-discipline Chinese evaluation suite for foundation models.

Feel free to reach out via email: `jliugi [at] connect.ust.hk`.

## Recent News

- **Feb 2025** &mdash; Started a research internship at MINIMAX.
- **Sept 2024** &mdash; Joined HKUST as a Ph.D. student in the NLP group, advised by Prof. Junxian He.
- **Jun 2024** &mdash; Graduated from Shanghai Jiao Tong University with a B.Eng. degree.
- **2024** &mdash; "On the Universal Truthfulness Hyperplane Inside LLMs" accepted to EMNLP 2024.
- **2024** &mdash; "In-Context Sharpness as Alerts" accepted to ICML 2024.

## Publications

A full list is available on the [Publications]({{ '/publications/' | prepend: site.baseurl }}) page. Below is a chronological mirror:

{% assign sorted_pubs = site.publications | sort: "date" | reverse %}

{% for pub in sorted_pubs %}
  <div class="pub-entry" style="margin-bottom: 1.2em;">
    <p style="margin: 0;">
      <strong>{{ pub.title }}</strong><br>
      <span style="color: #555;">{{ pub.date | date: "%Y" }} &middot; <em>{{ pub.venue }}</em></span>
    </p>
    <p style="margin: 0.3em 0; font-size: 0.92em; color: #333;">
      {{ pub.citation | strip_html }}
    </p>
    <p style="margin: 0.3em 0; font-size: 0.92em;">
      {% if pub.paperurl and pub.paperurl != '' %}
        <a href="{{ pub.paperurl }}">[Paper]</a>
      {% else %}
        <span style="color: #888;">[Paper link coming soon]</span>
      {% endif %}
      <a href="{{ pub.url | prepend: site.baseurl }}">[Details]</a>
    </p>
  </div>
{% endfor %}

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology (HKUST) &mdash; 2024 &ndash; Present
- **B.Eng.**, Shanghai Jiao Tong University (SJTU) &mdash; 2020 &ndash; 2024

## Research Experience

- **Research Intern, MINIMAX** &mdash; Feb 2025 &ndash; Present
- **Research Intern, Tencent WXG** (advised by Zifei Shan) &mdash; Jun 2024 &ndash; Sep 2024
- **Research Intern, Shanghai AI Lab** (advised by Prof. Yu Cheng) &mdash; Jun 2023 &ndash; Dec 2023

## Skills

- **Research areas:** Large Language Models, Reasoning, Reinforcement Learning, Vision-Language Models, Hallucination Mitigation, Truthfulness, Interpretability
- **Methods & tools:** Deep Learning, PyTorch, Hugging Face Transformers, Mechanistic Interpretability, Data Synthesis

## Contact

- **Email:** jliugi [at] connect.ust.hk
- **GitHub:** [@Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://twitter.com/junteng88716710)
