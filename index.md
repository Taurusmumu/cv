---
layout: cv
title: Jiamu Wang
email: taurusmumu@gmail.com
phone: 
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
- Korean - Fluent talking and reading (TOPIK 5) 


## SKILLS

- Java, Python, JavaScript, TypeScript, HTML5, CSS3, SQL, Neo4J, Swift
- Spring MVC/BOOT/DATA/CLOUD, Maven, OpenCV, Keras, Sklearn, Jupyter Notebook, Flask, Nginx, Gunicorn, NodeJS,
jQuery, Express, Webpack, Docker, Kubernetes, Microservices, Prometheus, Jira, AWS


## PUBLICATION

- https://conf.researchr.org/profile/ase-2021/jiamuwang


## PROFESSIONAL EXPERIENCE

### __EBAY, Full-Stack Engineer__ `Shanghai, China`
```
July 2018 – July 2020
```
__Root Cause Analysis (RCA) System__

- EBay structure is based on microservice architecture that has over 5k clusters running on **Kubernetes**. To help TDO team figure out the RC of any failure triggered by supervisor system and reduce man-check time, I took part in developing an automated RCA system, written in **Flask**, capable of handling 300+ QPS in benchmark.
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




<!-- ### Footer

Last updated: Mar 2022 -->
