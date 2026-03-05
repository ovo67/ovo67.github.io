---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======
* 2023年至今：清华大学电子系，博士研究生
  * 导师：姚权铭教授

* [请添加本科教育经历]

研究经历
======
* [请添加研究经历]

技能
======
* Python
* 机器学习
* 深度学习
* [请添加其他技能]

发表论文
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

学术报告
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

教学经历
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
