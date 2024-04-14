# Game 2048

## Description

Game 2048 is a popular single-player sliding block puzzle game. The objective is to slide numbered tiles on a grid to combine them and create a tile with the number 2048. The game continues until no moves are possible or until the 2048 tile is achieved.

## Deployment

The Game 2048 application has been deployed on an Amazon EKS (Elastic Kubernetes Service) cluster. Amazon EKS is a managed Kubernetes service that makes it easy to deploy, manage, and scale containerized applications using Kubernetes on AWS.

The deployment includes using Kubernetes resources such as Deployments and Services to ensure the availability and accessibility of the game application.

## Usage

Users can access the deployed Game 2048 application through an Application Load Balancer (ALB) Ingress Controller, which manages incoming traffic and directs it to the appropriate services within the EKS cluster.
