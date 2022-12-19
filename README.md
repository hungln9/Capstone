[![CircleCI](https://circleci.com/gh/hungln9/Capstone.svg?style=shield)](https://circleci.com/gh/hungln9/Capstone)

# Udacity Cloud DevOps Capstone Project

This is final project of Udacity Cloud DevOps Engineer Nanodegree Program.

## Project Overview
Using [Udacity-Project5](https://github.com/hungln9/Capstone) as the base app for deploying to AWS EKS. Upgrade CircleCI yaml to build and push docker to Docker Hub, then deploy to AWS EKS

## Project Files

#### infrastructure

- config.yml

#### EKS-resources
- deployment.yml
- service.yml

#### Dockerfile

This is Dockerfile of application:
- Dockerfile

## Notes
- Included [screenhots](https://github.com/hungln9/Capstone/tree/main/screenshots)
- Using CircleCI Orbs to automate AWS tasks
- Using region us-east-1

## Load BalancerS
http://a90e369f55ec94ea69dc6b8de35e4b8e-506090521.us-east-1.elb.amazonaws.com/

