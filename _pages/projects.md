---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

# Projects

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
