---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download Resume Here](https://drive.google.com/file/d/1ArukvhWEMHiAkwiORYjLLzY7os7iC5Uc/view?usp=sharing)

Education
======
* B.Tech. in Electrical Engineering, Delhi Technological University (Formerly Delhi College of Engineering), 2019
* M.S. in Information Systems, Carnegie Mellon University, 2024 (Current)

Work experience
======

## Cult.fit (Formerly Cure.fit)
* Senior Full Stack Software Engineer (Jan 2023 - Jul 2024)
  * Implemented web scrapper scheduler engine for scrapping 10000+ 1P and competitor SKUs daily on marketplaces like Amazon, Flipkart, etc. providing visibility to market price sensitivity. Used webscraper.io and SmartProxy (3P) to dodge rate-limiting.
  * Implemented delayed payments and fulfilment processor addressing issues like delayed payment confirmation from payment gateways and middleware which lead to on overall conversion bump of 3.9% and net revenue by 0.8%.
  * Redefined address flows for the cult.sport e-commerce website adding new features like address editing, fetching current location, address auto-completion, address aliasing and order confirmation preview leading to 8% drop in O2C and address addition by 1.6.
  * Onboarded and maintained Appsmith and Retool on EC2 instances in the internal VPC, solving for 50+ internal business and operations dashboards.
  * Integrated and maintained MoEngage (3P) on the cult.sport e-commerce website for enabling event driven interaction and user experience personalisation. Solved for 1M+ daily user comms over various channels. Solved for 2-way interaction with Cure.fit tech infrastructure using AWS SQS and SNS.
* Full Stack Software Engineer (Feb 2020 - Dec 2022)
  * Built a caching service using Node JS,AWS Lambda, Redis and MongoDB. Migrated the in-memory caches of several micro service servers.Achieved an overall 30% drop in MongoDB and MySQL load, significant reduction of infrastructure costs and reduced the startup time of micro service servers by around 20%.
  * Migrated critical endpoints from Node JS GatewayAPI to Spring Boot reducing the latencies from 350ms to less than 100ms.
  * Modelled and built an organisation wide cart service using Node js and MongoDB for aggregating user cart based on verticals.
  * Lead the front end track of Food Marketplace (Aggregator of healthy food vendors) building animated UI flows using react native, redux and styled components library.
  * Modelling and built order management, offers, discounts, user feedbacks and other critical flows of Food Marketplace.
* Frontend Engineer (Jun 2019 - Jan 2020)
  * Actively contributed to Cure.fit React-Crux, an open source UI library for CRUD operations on server side entities using fundamentals of React, flex-box and Redux.
  * Implemented numerous responsive, highly configurable and dynamic mobile application screens with optimized performance in react native and wiring them with the Gateway API layer (MVC architecture) using Node JS, Inversify JS and Typescript.
  
Skills
======
* **Languages**: Java, Python, C++, SQL, Javascript, Typescript, HTML5, CSS, MQL (MongoDB), Bash
* **Frameworks and Libraries**: Spring Boot, React, React Native, Redux, Node JS, Express JS, Gulp, Numpy, Scikit-learn
* **Databases and Tools**: MySQL, PostgreSQL, MongoDB, Redis, Jenkins, Postman, Zeplin, git, Lerna, Maven, npm

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
