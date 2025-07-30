# 📈 Kafka Stock Market Project

This project is a simple Kafka-based data pipeline that transfers stock market data from a local source to an AWS S3 bucket. The system is built for testing real-time data transfer mechanisms using Apache Kafka running on an AWS EC2 instance.

---

## 🚀 Project Overview

- Data is streamed **from local storage** to **AWS S3** using Apache Kafka.
- Kafka is hosted on an **EC2 instance**.
- Data is sent in **chunks of 100 records** to ensure smooth and controlled transmission.
- This project serves as a proof of concept for cloud-based Kafka pipelines.

---

## 🧱 Architecture

![Kafka Architecture](https://private-user-images.githubusercontent.com/115441787/467599724-23f447ca-6aef-4b48-8fae-dbe3d5420680.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTM4NDU0MDYsIm5iZiI6MTc1Mzg0NTEwNiwicGF0aCI6Ii8xMTU0NDE3ODcvNDY3NTk5NzI0LTIzZjQ0N2NhLTZhZWYtNGI0OC04ZmFlLWRiZTNkNTQyMDY4MC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNzMwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDczMFQwMzExNDZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kNWZjNzRkNTJjNzIwOTJjODIxODVjZDhmM2IzNjY3NmExYTM5NmIzNzhhNDhjMjZlYTQ5OTA0OTQ3MjZmYmQyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.r18EBM7SAPkgDQgrpFbmmQdPc4DJWx-XV9kxRoVi9EE)


