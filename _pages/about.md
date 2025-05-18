---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

✨ Research Interest
======
- Video Generation and Understanding
- Multimodal Large Models
- Multimodal Agent

Specific work can be found in: [Publications](https://zhengrongyue.github.io/publications/).

📑 Publications
======
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



🤵🏻 Career
======
PhD: Shanghai Jiao Tong University & Shanghai AI Lab, 2024~Present

Intern：Natural Language Understanding (NLU) Lab, Samsung R&D Institute China - Beijing (SRC-B), 2024.09~2024.11

Bachelor: Department of Computer Science and Technology, China University of Mining and Technology (Beijing), 2020~2024


🏅 Awards
======
The 23td China Robotics and Artificial Intelligence Competition Intelligent Sorting Challenge (National No. 1) National First Prize(2022)

The 17th National Undergraduate Smart Car Competition Xunfei Creative Group (National Top Four) National First Prize(2022)

The 15th National College Student Energy Conservation and Emission Reduction Social Practice and Science and Technology Contest, National Third Prize(2022)

The 15th China Undergraduate Computer Design Contest Provincial Third Prize(2022)

The 15th Beijing College Students Physics Experiment Competition Provincial Third Prize(2022)

The 4th Beijing University Student Energy Conservation and Water Conservation Contest Provincial Second Prize(2022)


📑 Professional Activity
======
Attend CVPR 2023 Beijing Workshop, 2023.06
