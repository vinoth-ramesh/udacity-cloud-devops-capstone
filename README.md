# Capstone project for Udacity's AWS Cloud DevOps Nanodegree

*Microservices Orchestration with Kubernetes using Jenkins CI/CD Pipeline*

The goal of the project is to set up a Kubernetes (k8) cluster using AWS Elastic Kubernetes Service (EKS) to deploy a docker image leveraging Jenkins CI/CD Pipeline. 

---

## Project Info
A simple python app, app.py was created using Flask that displays a simple web page. This simple app was created to illustrate how apps can be contanerized with docker and used as microservice with the use of kubernetes.

## Branches

master => This branch contains the latest code that is running is production. So this could be from green or blue branch (space, space)
blue => This branch contains code for implementing blue service deployment (space, space)
green => This branch contains code for implementing green service deployment

## Deployment type

This project implements a solution for blue/green deployment to achieve a zero-dowmntime deployment. /OutputFiles/01-Udacity AWS DevOps Capstone project.pdf shows a high-level diagram for this implementation

## OutputFiles

* **01-Udacity AWS DevOps Capstone project.pdf**: Network diagram for the project
* **02-lint-fail.png**: screenshot to indicate failure on lint stage
* **03-security-scan.png**: screenshot indicates pipeline with aquascan
* **04-ec2.png**: screenshot to indicate ec2 instances used in the k8 cluster and the jenkins instance
* **05-loadbalancers.png**: aws loadbalancers used for deploying each service.
* **06-eks-clusters.png**: screenshot to indicate clusters names that were in created in aws.
* **07-blue-pipeline-success.png**: screenshot indicates pipeline for blue service was successful
* **08-blue-webpage.png**: screenshot to indicate updated app for blue service
* **09-green-pipeline-success.png**: screenshot of green service webpage for first version of app
* **10-green-webpage.png**: screenshot to indicate updated app for green service.
* **11-route53.png**: screenshot to indicate the dns service used 

---

## Resources

* [Nirmata series on Kubernetes](https://www.eksworkshop.com/030_eksctl)
* [CI/CD with Jenkins, Docker and Kubernetes on AWS](https://medium.com/@Thegaijin/ci-cd-with-jenkins-docker-and-kubernetes-26932c3a1ea)

