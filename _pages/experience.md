---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Professional Experience
======

{% for post in site.experience reversed %}
  {% include archive-single-experience.html %}
{% endfor %}

Education
======
* M.S. in Information Systems and Management, Carnegie Mellon University, 2025 (Expected)
  * GPA: 4.0/4.0 (Dean's List)
  * Coursework: Introduction to Machine Learning, Introduction to Deep Learning, AI Engineering, Distributed Systems, Object Oriented Programming in Java, Database Management Systems, Linear Programming, Agile Methods, Data Structures

* B.Tech in Electrical and Computer Engineering, Delhi Technological University (Formerly Delhi College of Engineering), 2019
  * GPA: 3.78/4.0 (First Class with Distinction)

Skills
======
* Languages: Java, Python, SQL, Javascript, Typescript, HTML, CSS, MQL (MongoDB), Bash (Shell), C++
* Frameworks/Libraries: 
  * Spring Boot, React, React Native
  * Redux, Node.js, Express.js
  * Gulp, PM2, JUnit, Nose2, Jest
* Databases/Tools: 
  * MySQL, PostgreSQL, MongoDB, Redis
  * Maven, NPM, GCP, AWS, Docker, Kubernetes, Kafka, Coralogix
* Others: 
  * Software Development Life Cycle (SDLC)
  * Agile Principles, Stakeholder Management
  * JIRA, Postman, Version Control (git)

Research Publications
======
* Classification of Power Quality Events Using Hybrid CNN and SVM at IEEE CoDIT'19, Paris, France
  * Developed a hybrid deep learning model using CNN and SVM to accurately detect and classify various power quality events like voltage swell, sag, etc. The proposed architecture had a classification accuracy of 97.98%.

* Attention-Guided Deep CNN for Skin Cancer Detection and Classification at IEEE IPTA'19, Istanbul, Turkey
  * Employed attention mechanism in D-CNN architecture over pre-trained image recognition models. Achieved classification accuracy of 85.8% on skin cancer types like Basal-cell carcinoma (BCC), Squamous-cell carcinoma (SCC) and Melanoma.

Projects
======
* **AI Sentiment Analysis Platform - CMU & Harley-Davidson Collaboration**
  * Developed a Django web app using Hugging Face, PyTorch, NumPy, and pandas for automated sentiment analysis of user comments.
  * Implemented a responsive UI with Django templates and CSS, applying Harley-Davidson's signature color scheme and typography.
  * Containerized the application with Docker and delivered a production-ready image for Harley-Davidson's internal deployment.

* **Movie Recommender System**
  * Deployed Django application on a VM with load balancer using Docker containerization and SQLite database serving 1M users.
  * Automated CI/CD pipelines using Jenkins for deployment and GitHub Actions for PR test automation using Nose2 Python library.
  * Integrated collaborative filtering model with telemetry to track drift using Prometheus and Grafana, with automated model retraining.

* **Goal Keeper (GoalLive)**
  * Implemented a Streamlit-based Python application to identify user's free time slots using Google Calendar API.
  * Recommended football matches, nearby restaurants (via geolocation and Yelp API), and online match streaming options.
  * Scraped match schedules using Selenium headless browser (Chrome) driver and improved performance through caching.

* **Covi-help Mobile Application**
  * Developed a cross-platform react native application leveraging the Government of India open source RESTful APIs as data source.
  * Integrated AWS Code Pipeline for CI/CD, AWS EC2 hosted Inversify.js RESTful web service, and Redis for caching static data for avoiding rate-limiting and AWS S3 and CloudFront CDN for storing and caching static and dynamic assets.
