---
layout: project
title: narly.us
group: projects
project :
  name : narly.us
  tagline : "Narly is a (redis-based) tagging system for GitHub projects."
  source : http://github.com/plusjade/narly
  website : http://narly.us
  tagGroups :
    -
      name : platforms
      tags : [{name : web, why : "I'm a web guy first and foremost."}]
    -
      name : languages
      tags :
        -
          {name : ruby, why : "I am most proficient in ruby." }
        - 
          {name : HTML, why : "HTML is needed for the website."}
        -
          {name : CSS, why : "CSS is needed for the website."}
        - 
          {name : javascript, why : "Javascript is needed for asynchronously updating the page and user interactions such as tag unions/intersections."}
    -
      name : data
      tags : 
        - 
          {name: "redis", why : "Redis is used to store all data relating to 'tags'. I chose redis for its sheer speed as it handles unions and intersections (of tags) natively. With mysql you'd have to cache the tag queries to make them useable." }
        - 
          {name: "mysql", why : "Mysql is use to store user data for authentication via Omniauth with GitHub as the OAuth provider."}
        - 
          {name: "dataMapper", why : "DataMapper is used as the ORM because it is simpler, lighter, lower-level, and more straight-forward than active-record." }
    -
      name : frameworks
      tags :
        -
          {name : rails-3, why : "Rails 3 is used as the RESTful app server. Moving forward I hope to learn to use the simplest tool for the job - because rails isn't simple enough for me." }
        -
          {name : backbone.js, why : "Backbone.js is used as a way for tags, users, and repositories to automatically update themselves in the UI when changes occur. Backbone also enables pushState for seamless back and forward navigation."}
        -
          {name : require.js, why : "Require.js is used to manage all my javascript code. Require.js brings structure and good practices to javascript development. ex: Asynchronous Module Definition, closure, minifying/packaging, standardized file-structure)"}
        -
          {name : jquery, why : "jQuery is the defacto way to interact easily with the DOM."}
        - 
          {name : twitter-bootstrap, why : "I chose twitter bootstrap as a way to standardize and speed up design iteration."}
    -    
      name : infrastructure
      tags : [{name : "nginx", why : "Very simple to setup web server."}, {name : "ec2", why : "ec2 is a very economical choice. I'm using one linux-micro for the rails app server + mysql database and one linux-micro dedicated to the redis server."}]
    -
      name : templating
      tags : [{name : mustache, why : "Mustache for javascript is used to render the backbone views. I like mustache because it is very developer-oriented (it's sensible imo)."}]
    -
      name : api
      tags : [{name: "REST", why : "REST endpoints for all data so we can load it easily into the UI via javascript."}, {name: "json", why : "JSON is used as the primary data interface between application and client."} ]

---


## Overview 

Hello Jello

## Motivation

blah

## Lessons

asdf
