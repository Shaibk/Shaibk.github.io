---
permalink: /
title: "Binke Zhao"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Undergrad  

**About Me**

I am currently an remote intern in CLab under the supervision of Professor [Xinyu Chen](https://soldierchen.github.io/), and I was an intern of Professor [Jian Weng](https://were.github.io/) at KAUST during June 2025 to September 2025. I will graduate in 2026 from the University of Electronic Science and Technology of China under a [customized interdisciplinary curriculum](https://icse.uestc.edu.cn/info/1057/4103.htm). I am actively seeking Ph.D. opportunities in research groups dedicated to cutting-edge computer architecture.

My research interests span the full hardware–software stack, from next-generation efficient AI to microprocessor architectures. I am passionate about designing innovative systems that bridge high-level programming models with efficient hardware implementations, enabling breakthroughs in performance, scalability, and adaptability.

**Education**

- UESTC (B.Eng. in Integrated Circuit Design, Sep 2022 – Jun 2026)
- Khalifa University (Exchange Student, Jan 2025 – May 2025)

## Publications {#publications}

{% assign pubs = site.publications | sort: 'year' | reverse %}
{% for post in pubs limit: 10 %}
  {% include archive-single.html %}
{% endfor %}
