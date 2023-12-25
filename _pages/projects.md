---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
classes: wide

feature_row0-1:
  - image_path: /images/exp.gif
    alt: "Exp"
    title: "Exp"
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


---

## Projects

{% include feature_row id="feature_row0-1" type="left" %}
<a name="Exp"></a>


## Projects in Data Science

&nbsp;
<a name="Signal-Processing">
{% include feature_row id="feature_row1-0" type="left" %}



