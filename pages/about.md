---
layout: page
title: About
description: 写代码，解决问题
keywords: canhui shen, 沈灿辉
comments: true
menu: 关于
permalink: /about/
---

我叫沈灿辉，英文名: JornShen

## EDU

*　undergraduate: computer science, XMU  ---(2014 ~ 2018)

## Contact

* GitHub：[@jornshen](https://github.com/jornshen)
* 博客：[{{ site.title }}]({{ site.url }})

## Motto

* while (!dead) {study(); create();}
* stady foolish, stady hungry !

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Mobile Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_technological_framework_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Hobbies Keywords
<div class="btn-inline">
    {% for keyword in site.hobbies_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
