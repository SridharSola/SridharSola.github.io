---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true


feature_row0-1:
  - image_path: assets/gif/gifify.gif
    alt: "AWS app demo"
    title: "Gifify App"
    text: "I developed a Gifify app where a user can upload a video and get it processed into a gif. This is a Flask app deployed to AWS EC2 instance. The user login data is saved into DynamoDB, while the users' uploaded videos and resulting gifs are stored on S3 buckets. The video processing is implemented through a Lambda function (deployed via Docker to ECS)."
    url: "https://github.com/k-bosko/gifify"
    btn_label: "Code"
    btn_class: "btn--primary"
    tags:
        - AWS
        - Lambda
        - S3
        - EC2
        - DynamoDB
        - Flask
        - ECS
        - Docker

feature_row0-2:
  - image_path: assets/gif/wumpus.gif
    alt: "Java game demo"
    title: "Hunt the Wumpus Game"
    text: "Java-based implementation of the '73 classics [\"Hunt the Wumpus\"](https://en.wikipedia.org/wiki/Hunt_the_Wumpus), using MVC design pattern and object oriented programming (OOP). The game can be played in both GUI and text-based modes."
    url: "https://github.com/k-bosko/HWT"
    btn_label: "Java code"
    btn_class: "btn--primary"
    url2: "https://github.com/k-bosko/HWT"
    btn_label2: "UML Diagram"
    btn_class: "btn--primary"
    tags:
        - Java
        - MVC
        - OOP
        - UML

feature_row0-3:
  - image_path: assets/gif/ghostkitchen.gif
    alt: "Node.js app demo"
    title: "GhostKitchen App"
    text: "In a series of GhostKitchen projects, I teamed up with another student to develop a Node.js app that supports CRUD operations for processing new orders for a restaurant chain. The app has 3 versions that differ in database used for backend - one version is based on SQLite, another on MongoDB and yet another on Redis."
    url: "https://github.com/k-bosko/GhostKitchen"
    btn_label: "SQL code"
    btn_class: "btn--primary"
    url2: "https://github.com/k-bosko/GhostKitchen-II"
    btn_label2: "MongoDB code"
    btn_class: "btn--primary"
    url3: "https://github.com/k-bosko/GhostKitchen-III"
    btn_label3: "Redis code"
    btn_class: "btn--primary"
    tags:
        - Node.js
        - SQL
        - MongoDB
        - Redis
        - Bootstrap

feature_row0-4:
  - image_path: assets/gif/best_companies.gif
    alt: "Forbes 500 best companies for work"
    title: "Best Companies for Work App"
    text: "In this project, I teamed up with another student to develop a Python app to explore Forbes 500 best companies to work for. I was responsible for web scraping, data cleaning, creating a SQLite database and data visualizations."
    url: "https://github.com/k-bosko/Best_Companies_to_Work_For"
    btn_label: "Code"
    btn_class: "btn--primary"
    tags:
        - Python
        - SQLite
        - OOP
---
