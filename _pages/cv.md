---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download Resume Here](http://nisheetdas1.github.io/files/resume.pdf)

Summary
======
Backend focused Full Stack Engineer with 5 years of zero-to-one engineering ownership, designing and scaling mission-critical services. Adept in responsive designs, caching architectures and cross-functional delivery across product and engineering.

Education
======
* **Master of Information Systems Management** - Specialization in Software Engineering, Carnegie Mellon University, Pittsburgh, PA (August 2025)
  * GPA: 4.0/4.0
  * Coursework: Machine Learning, Deep Learning, AI Engineering and MLOps, Distributed Systems, Object Oriented Programming in Java, Database Management Systems, Linear Programming, Agile Methods, Data Structures and Algorithms

* **Bachelor of Technology in Electrical Engineering**, Delhi Technological University (Formerly Delhi College of Engineering), New Delhi, India (June 2019)
  * GPA: 3.78/4.0 (First Class with Distinction)

Professional Experience
======

## Cure.fit - Fitness Tech Unicorn, Bangalore, India
**Full Stack Software Engineer - E-Commerce** (June 2019 - July 2024)

* Designed and led the integration of Cult.sport into an internal telesales platform, including product modeling, discount logic, customer lifecycle management, and telesales agent UI, driving a 10% revenue increase.
* Cross-functioned with central payments team to implement a multi-tenant delayed/failed payments and fulfillment processor, addressing payment gateway webhook delays/failures. Increased conversion rates by 3.9% and net revenue by 0.8%.
* Optimized system performance by building a caching service, onboarding in-memory caches for multiple micro-services. Led to 30% drop in database load, lower infrastructure costs and ~20% faster server startup times through AWS Lambda triggers.
* Built a web scraping scheduler engine to extract 10,000+ SKUs daily from marketplaces using webscraper.io and SmartProxy, saving ~3 days/week of manual effort by 3 analysts and accelerating pricing decisions and catalog quality.
* Redesigned address management flows for Cult.sport, adding features like address editing, auto-completion, location detection, and order confirmation, reducing order cancellations by 8% and increasing addresses added per user by 1.6.
* Drove a strategic initiative to deploy low-code tools Appsmith and Retool on EC2 instances within a secure VPC with VPN-only access, integrating with internal services to power 100+ critical dashboards and cutting development time by ~80%.
* Integrated MoEngage on Cult.sport for personalized event-driven CRM interactions, supporting ~1M daily user communications and 1M website events. Enabled two-way interaction with internal services using SQS, handling ~100k daily events.
* Migrated critical endpoints from Node.js Backend-for-Frontend (BFF) to Spring Boot reducing latency from 350ms to ~100ms.
* Led frontend development of Food Marketplace app from scratch using React Native and Redux; built Node.js/TypeScript backend supporting orders, taxes, discounts, and user feedback, onboarding 200+ vendors and 50k+ users within 6 months.
* Developed responsive mobile screens in React Native and integrated with a Node.js Backend-for-Frontend (BFF) using Inversify.js and TypeScript, ensuring user data privacy and security through minimal and controlled data exposure.

Technical Skills
======
* **Languages**: Java, Python, SQL, JavaScript, Typescript, HTML, CSS, Bash (Shell), C++
* **Frameworks/Libraries**: Spring Boot, React, React Native, Redux, Node.js, Express.js, Gulp, PM2, JUnit, Nose2, Jest
* **Databases/Tools**: MySQL, PostgreSQL, MongoDB, Redis, Maven, NPM, GCP, AWS, Docker, Kubernetes, Kafka, Coralogix, Splunk, JWT, OAuth, Datadog, JIRA, Postman, git
* **Others**: Software Development Life Cycle (SDLC), Agile Principles, Stakeholder Management, Test Driven Development (TDD)

Academic Projects
======

**AI Sentiment Analysis Platform** - CMU & Harley-Davidson Collaboration
* Developed a Django app using Hugging Face, PyTorch, NumPy and pandas for automated sentiment analysis of comments.
* Containerized the application with Docker and delivered a production-ready image for Harley-Davidson's internal deployment.

**Movie Recommender System**
* Deployed Django application on a VM with load balancer using Docker containerization and SQLite DB serving 1M users.
* Automated CI/CD pipelines with Jenkins for deployment and implemented Kubernetes-based blue-green deployments; configured GitHub Actions for pull request test automation using Nose2.
* Integrated collaborative filtering model with telemetry (Prometheus, Grafana) to monitor model drift, automate retraining, and dynamically update model weights from Docker-mounted volumes.

**Goal Keeper (GoalLive)**
* Implemented a Streamlit-based Python application to identify user's free time slots using Google Calendar API.
* Recommended football matches, nearby restaurants (via geolocation and Yelp API), and online match streaming options.
* Scraped match schedules using Selenium headless browser (Chrome) driver and improved performance through caching.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
