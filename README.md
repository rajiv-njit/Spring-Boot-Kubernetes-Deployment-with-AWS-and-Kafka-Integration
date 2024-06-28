# Spring Boot Kubernetes Deployment with AWS and Kafka Integration

## Project Name

**Project Name:** spring-boot-k8s-aws-kafka-integration

## Project Overview

This project demonstrates how to create a Spring Boot application, containerize it using Docker, deploy it on a local Kubernetes cluster using Minikube, and integrate it with various AWS services and Kafka.

## Prerequisites

Make sure you have the following installed on your local machine:
- Java Development Kit (JDK) 17
- Maven
- Docker
- Minikube
- kubectl
- AWS CLI (configured with appropriate credentials)

## Project Setup

1. **Set up Minikube:**
   Follow the guide to set up a single-node Kubernetes cluster with Minikube.

2. **Create a Spring Boot Application:**
   Use Spring Initializr to create a new project with the following options:
   - Java
   - Maven
   - Spring Boot version 3.x.x
   - Dependencies: Web, Actuator

