---
layout: project
title: pluspanda.com
group: projects
project :
  name : pluspanda.com
  tags :
    languages : [ruby, HTML, CSS, javascript]
    data : [mysql, active-record]
    frameworks : [rails-3, sinatra, jquery]
    infrastructure : [linode, heroku]    
    api : [REST, json, jsonp]
    platforms : [web]
---

## Overview 

Hello Jello

## Motivation

blah

## Lessons

asdfd

## Stack

{% for tagGroup in page.project.tags %}
  <h5>{{ tagGroup[0] }}</h5>
  <ul>
  {% for tag in tagGroup[1] %}
    <li>{{ tag }}</li>
  {% endfor %}
  </ul>
{% endfor %}