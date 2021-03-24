---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


## Statistical methodology

- **Dai, B.**, Shen, X., & Wong, W. (2020). Coupled generation. *Journal of the American Statistical Association*, in press. 
  - [html](https://doi.org/10.1080/01621459.2020.1844719) | [code](https://amstat.tandfonline.com/doi/suppl/10.1080/01621459.2020.1844719?scroll=top#.YFt5dUNKiV4)

- **Dai, B.**, Shen, X., & Wang, J. (2020). Embedding learning. *Journal of the American Statistical Association*, in press. 
  - [html](https://doi.org/10.1080/01621459.2020.1775614) | [code](https://amstat.tandfonline.com/doi/suppl/10.1080/01621459.2020.1775614?scroll=top#.YFt50kNKiV4) | [:octocat:](https://github.com/statmlben/embedding-learning) | [slides](https://www.researchgate.net/publication/346572305_slidespdf)

- **Dai, B.**, Shen, X., Wang, J., & Qu, A. (2019). Scalable Collaborative Ranking for Personalized Prediction. *Journal of the American Statistical Association*, in press.

- **Dai, B.**, Wang, J., Shen, X., & Qu, A. (2019). Smooth neighborhood recommender systems. *Journal of machine learning research*, **1**(24).

<!-- <sup>*</sup> Equal authorship statement -->