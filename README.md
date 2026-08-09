# Back-end Application Development Capstone Project

## About this Course
This is the final course in the IBM Backend Development Professional Certificate. This capstone project course will give you the chance to practice the work that back-end developers do in real life when working with applications. 

In this course, you will assume the role of a real-life developer working to develop and deploy back-end microservices and applications. 

You will be tasked to develop, deploy, and integrate an application composed of several microservices, and integrating them seamlessly. You will use various back-end tools and technologies, including Flask, Django, NoSQL, and Mongo DB, to accomplish this project while applying coding best practices. You will also deploy and scale and update each of the application’s microservices independently using Cloud Native technologies: Kubernetes, OpenShift and serverless (Code Engine).

In this course, you’ll mostly focus on hands-on work to demonstrate and apply what you have learnt in previous courses. By successfully completing this Capstone you will have added a project to your programming portfolio to showcase to employers.

## Syllabus

### Module 1: Getting Started
In the first module, you will learn about Flask, a lightweight python-based web application framework. The module will teach you how to create a Flask application that responds to user requests at specific URLs. You will also learn about handling both server and user errors. You will learn how to make external API calls from Flask. You will apply these lessons to create a service that produces pictures from past events.

- **My external API for this module can be found in the repo: [Back-End-Development-Pictures](https://github.com/c85/Back-End-Development-Pictures)**

## Module 2: Creating Get Songs Service with Flask
With the advent of Big Data and agile development methodologies, the database landscape has evolved with NoSQL databases gaining more importance and relevance. The main benefit of using NoSQL databases is the ability to effectively handle scalability and flexibility issues presented by the latest complex applications.

In this second module, you will learn various flavors of NoSQL database products and practice using them in multiple hand-on labs throughout the course. You will start by learning the history and the basics of NoSQL databases and discover their key characteristics and benefits. Then you will learn about the four NoSQL databases and how they differ from each other. You will further learn how to work with MongoDB shell. You will then get hands-on experience using MongoDB basic commands, querying, and connecting from Flask. You will create the songs microservice using MongoDB and Flask.

- **My microservice for this module can be found in the repo: [Back-End-Development-Songs](https://github.com/c85/Back-End-Development-Songs)**

## Module 3: Main Django Application
In the third module, you will get hands-on practice creating a Django application and connecting it to services. You will be asked to create a data model and use the Django migration tool to create the tables and relationships. You will then create controllers to implement business logic to send the appropriate data to the provided templates.

- **My Django application for this module can be found in the repo: [Back-End-Development-Capstone](https://github.com/c85/Back-End-Development-Capstone)**

## Module 4: Deploy your application and services
In Module 4, you will deploy your application and services using Code Engine, OpenShift, and Kubernetes. You will first learn about IBM Cloud code engine and how it helps in deployment of your applications. You will create a DockerFile for the Pictures and deploy it to IBM code engine. You will create a second DockerFile for the Songs microservice and deploy it to an OpenShift cluster. You will learn how to push the docker images for the microservices to IBM Container Registry. Finally, you will deploy the main application to IBM Kubernetes Service using YAML deployment files.

- **My deployment steps are catalogued in a collection of [screenshots](screenshots/) in [this repo](https://github.com/c85/ibm-bed-capstone)**

## Module 5: Final Submission and Peer Review
In the final module, you will need to submit the screenshots from the hands-on labs for peers to review. You will also need to provide URLs for the microservices and the Django application. In addition, you may be asked to submit GitHub repo links to enable peers to review your code. After you submit your project, you will need to review and grade one of your peer’s submissions.