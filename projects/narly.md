---
layout: project
title: narly.us
group: projects
project :
  name : narly.us
  tags :
    languages : [ruby, HTML, CSS, javascript]
    data : [redis, mysql, dataMapper]
    frameworks : [rails-3, backbone.js, require.js, jquery, twitter-bootstrap]
    infrastructure : [nginx, ec2]
    api : [REST, json]
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