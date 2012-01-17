---
layout: project
title: Mustache-with-Jekyll
group: projects
project :
  name : mustache-with-jekyll
  tags :
    languages : [ruby, HTML]
    templating : [mustache]
    platforms : [web]
---

## Overview 

Hello Jello

## Motivation

blah

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