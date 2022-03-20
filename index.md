---
layout: cv
title: Jiamu Wang
email: taurusmumu@gmail.com
phone: 13007073792
homepage:
    url: https://taurusmumu.wordpress.com/
    text: Blog
---
# Jiamu Wang


<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->
{% include cv-contact.html %}

## Education

### __University of Southern California__ `Los Angeles, CA`
```
Jan 2017 – Dec 2018
```
Master of Science in Electrical Engineering

### __Hefei University of Technology__ `Hefei, China`
```
Aug 2012 - Jun 2016
```
Bachelor of Science in Electronics Science and Technology

## LANGUAGE PROFICIENCY AND CERTIFICATES

- Mandarin - Native Speaker
- English - Fluent talking and reading (TOEFL 102) 
- Korean - Fluent talking and reading (TOPIK 5) <br>


## SKILLS

- Java, Python, JavaScript, TypeScript, HTML5, CSS3, SQL, Neo4J, Swift
- Spring MVC/BOOT/DATA/CLOUD, Maven, OpenCV, Keras, Sklearn, Jupyter Notebook, Flask, Nginx, Gunicorn, NodeJS,
jQuery, Express, Webpack, Docker, Kubernetes, Microservices, Prometheus, Jira, AWS


## LANGUAGE PROFICIENCY AND CERTIFICATES

- Mandarin - Native Speaker
- English - Fluent talking and reading (TOEFL 102) 
- Korean - Fluent talking and reading (TOPIK 5) <br>


## PUBLICATION

- https://conf.researchr.org/profile/ase-2021/jiamuwang


## PROFESSIONAL EXPERIENCE

### __EBAY, Full-Stack Engineer__ `Shanghai, China`
```
July 2018 – July 2020
```
__Root Cause Analysis (RCA) System__

- Since eBay structure is based on microservice architecture that has over 3k clusters running on the **Kubernetes** platform, to help TDO team figure out the root cause of any failure triggered by supervisor system and reduce man-check time, I took part in developing an automated RCA system, written in **Python Flask** framework, capable of handling 300+ QPS in benchmark.
- (Front-End) Developed dashboard Microservice, written in **TypeScript** along with **React**, **Recoil** and **Antd**, bundled by **Webpack**, consuming data from label-collect-validate flow in system to represent data report by using **Echart**.
- (Back-End) Developed data source Microservice, written in Java Spring, able to fetch data from multiple databases (e.g., **Prometheus** and Click house), and trigger alert on **Slack** in a format of Jfreechart and Puppeteer Snapshot.
- (Back-End) Optimized backend data with algorithms such as FFT and Pearson to denoise and categorize metrics.
- To apply WSGI standard for the system, utilized **Gunicorn** as application server, **Nginx** as reverse proxy and Supervisor as
process manager, and whole project is packed up with **Docker** and deployed onto **Kubernetes** cluster.
- Utilized Prometheus and **Grafana** dashboard to monitor the system and **Google Analytics** to watch user statistic.


## PROJECTS

__Stock Search Web App / IOS App__

- Developed Stock Quote, a database-driven Web Application, backed on **AWS** cloud platform (EC2 service), to assist financial analysts in visualizing financial metrics and finding stock information.
- Designed a stock tracking dashboard (JavaScript, HTML) to visualize up to 50+ technical indicators for each stock in forms of Dynamic-Updating Highchart, able to add/remove stocks onto/out of Favorite List.
- (Web) Accomplished server-side scripts on **NodeJS**, able to request real-time data (JSON) from Alpha Vantage API.
- (IOS) Built server-side in Swift MVC and used Alamofire library to request data from public API.
- Built responsive user interface on **Bootstrap** Framework, implemented it to cross client-side interface.

__Data RESTful APIs & Microservices for Air Sensor Tracking System in Java Spring__
- Designed and implemented RESTful API to publish & monitor air quality data from sensors in Java, Spring Boot, Spring Cloud, capable of handling 3000+ QPS in the benchmark.
- Developed Dashboard Microservice in JavaScript, Spring Boot, WebSocket, STOMP to display real-time air data.
- Built Data Ingestion Microservice to validate, preprocess data, and publish to RabbitMQ as data broker for decoupling.
- Adopted Docker for configuration, deployment, scaling to improve development productivity.
- Utilized **Eureka** to monitor the system and improve the stability of Tracking Service.




<!-- ### Footer

Last updated: Feb 2019 -->
