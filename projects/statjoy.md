---
layout: project
title: statjoy.com
group: projects
project :
  name : statjoy.com
  tags :
    languages : [ruby, HTML, CSS, javascript]
    data : [localStorage]
    frameworks : [rails-3, jquery-mobile]
    infrastructure : [linode]
    platforms : [web, mobile]
---

## Overview 

Hello Jello

## Motivation

COolbingsa

## Lessons 

asdf


## Stack

{% for tagGroup in page.project.tags %}
  <h5>{{ tagGroup[0] }}</h5>
  <ul>
  {% for tag in tagGroup[1] %}
    <li>{{ tag }}</li>
  {% endfor %}
  </ul>
{% endfor %}