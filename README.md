# AWS-Employee-Directory-Application
<p style="text-align: justify;">
  A hands-on AWS cloud lab demonstrating how to configure an employee directory application with Amazon S3 for employee photos, Amazon
  DynamoDB for employee records, and IAM role-based access.
<p/>

## Project Overview
<p style="text-align: justify;">
  In this lab, I configured an employee directory web application hosted on an Amazon EC2 instance. I connected the application to an S3
  bucket for employee images and a DynamoDB table for employee information.
<p/>

<p style="text-align: justify;">
  The project demonstrates core AWS architecture concepts including object storage, NoSQL data storage, IAM permissions, and application-to
  service integration.
<p/>
<p style="text-align: justify;">
  Lab environment: This project was completed in a guided AWS lab environment with pre-provisioned networking and an EC2-hosted application.
<p/>

## Architecture

<p align="center">
  Website diagram (First Edition)
  <img width="2856" height="1806" alt="image" src="https://github.com/user-attachments/assets/edc20270-c075-4777-8ec7-bc6803a95cbc" />
</p>

## Website Components

| AWS Service | Role in the Website | Key Features |
|---|---|---|
| Amazon EC2 | Hosts the website's backend application and processes user requests. | Compute capacity, scalable instances, application hosting |
| Amazon DynamoDB | Stores and retrieves application data, such as user profiles, sessions, and website records. | NoSQL database, low-latency access, automatic scaling |
| Amazon S3 | Stores static website assets, including images, CSS, JavaScript, and uploaded files. | Object storage, high durability, scalable storage |

## Website Demonstration


