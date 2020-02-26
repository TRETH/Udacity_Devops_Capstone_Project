# Udacity_Devops_Capstone_Project

Apply the skills and knowledge which were developed throughout the Cloud DevOps Nanodegree program.

The following topics were covered with this capstone project:

- Working in AWS
- Using Jenkins to implement Continuous Integration and Continuous Deployment
- Building pipelines
- Working CloudFormation to deploy clusters
- Building Kubernetes clusters on AWS
- Building Docker containers in pipelines and pushing these containers to Docker Hub.

# Deployment strategy

This project showcases a blue/green deployment strategy for two different versions on nginx running within a docker container on an AWS Kubernetes Cluster.

This project utilises templating of the kubernetes deployment scripts for creating

- Deployments
- Services

on an AWS Kubernetes Cluster.

At the beginning of the blue/green deployment two kubernetes deployments of type blue are being created on the cluster. 

This follows best practices to test an update of the existing version of the blue nginx version in the green environment. 
