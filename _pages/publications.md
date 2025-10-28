---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
  
---  

Conference Papers
======

- ![INFOCOM](https://img.shields.io/badge/INFOCOM-2025-005f73?style=for-thebadge&colorA=005f73&colorB=ffb703) **CARE: Compatibility-Aware Incentive Mechanisms for Federated Learning with Budgeted Requesters**  
  **Xiang Liu**, Hau Chan, Minming Li, Xianlong Zeng, Chenchen Fu, Weiwei Wu  
  In Proceedings of *IEEE Conference on Computer Communications (INFOCOM)*, 2025.   
  [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11044535)  

- ![AAAI](https://img.shields.io/badge/AAAI-2025-005f73?style=for-thebadge&colorA=005f73&colorB=ffb703) **Non-stochastic Budgeted Online Pricing with Semi-Bandit Feedback**  
  **Xiang Liu**, Hau Chan, Minming Li, Weiwei Wu, Long Tran-Thanh  
  In Proceedings of *the AAAI Conference on Artificial Intelligence (AAAI)*, 2025.   
  [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/34089/36244)  

- ![IJCAI](https://img.shields.io/badge/IJCAI-2024-005f73?style=for-thebadge&colorA=005f73&colorB=ffb703) **Budget feasible mechanisms: A survey**  
  **Xiang Liu**, Hau Chan, Minming Li, Weiwei Wu    
  In Proceedings of *the 33rd International Joint Conference on Artificial Intelligence (IJCAI)*, 2024.   
  [[PDF]](https://www.ijcai.org/proceedings/2024/0899.pdf)  
---

Journal Papers
======
- ![TMC](https://img.shields.io/badge/TMC-2025-005f73?style=for-thebadge&colorA=005f73&colorB=ffb703) **Budget-Feasible Diffusion Mechanisms for Mobile Crowdsourcing in Social Networks**  
  **Xiang Liu**, Weiwei Wu, Minming Li, Wanyuan Wang, Yifan Qin, Yingchao Zhao, Junzhou Luo  
  In *IEEE Transactions on Mobile Computing (TMC)*, 2025.   
  [[PDF]](https://ieeexplore.ieee.org/iel8/7755/4358975/10938284.pdf)  

<!-- {% include base_path %}

<!-- New style rendering if publication categories are defined -->

<!-- {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} --> 


