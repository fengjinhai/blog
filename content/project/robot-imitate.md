+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Robot Imitate User Behavior"

# Project summary to display on homepage.
summary = "Robot simulation user likes, comments, etc."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "boards.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["information extraction"]

# Optional external URL for project (replaces project detail page).
#external_link = "http://example.org"

# Does the project detail page use math formatting?
math = false

+++

* 数据源
  * 某搜索引擎网页库
  * [Common Crawl Corpus](http://commoncrawl.org/)
* 根据号码在网页中出现的位置采用相应的方法
  * meta标签、microdata：结构化数据抽取
  * 网页头尾：基于规则的抽取系统
  * **网页正文**：
      - 人工总结号码信息特征（HTML标签结构特征，文本特征等）
      - 机器学习进行信息抽取和分类
