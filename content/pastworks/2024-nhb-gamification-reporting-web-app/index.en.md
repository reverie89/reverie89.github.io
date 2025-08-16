---
layout: "pastworks"
date: "2024-08-01"
title: "NHB gamification reporting web app"
tags:
  - "corporate"
showcase:
  - src: "2024_nhb_reporting_1.webp"
    alt: "Report generation dashboard for NHB gamification web app."
  - src: "2024_nhb_reporting_2.webp"
    alt: "Data decryption and analysis interface for NHB reporting app."
---
This project is a mobile-responsive web application designed for NHB to generate reports from AWS DynamoDB data. It features secure email decryption using NodeJS and AWS Secrets Manager, and leverages Python libraries for data processing. The app is built with an MVC architecture and deployed using Docker, ensuring scalability and maintainability for corporate reporting needs.

- Web app to generate reports from data downloaded from AWS DynamoDB
- Decrypt email addresses using encryption key (stored in AWS Secrets Manager), IV, salt, developed by vendor in NodeJS
- Python 3rd party libraries: gunicorn, flask, pandas, cryptography
- Designed with MVC. Docker/Python/Bootstrap stack
- Mobile responsive
