# Operationalizing-an-AWS-ML-project
This project helps in deploying an image Classification model from training to deploying .

The completed project contains code that trains and deploys an image classification model on AWS Sagemaker. Our goal in this project will be to use several important tools and features of AWS to adjust, improve, configure, and prepare the model we started with for production-grade deployment. Taking raw ML code and preparing it for production deployment is a common task for ML engineers, and it's very important for the following reasons:

* ML code alone isn't sufficient for most business scenarios. Real business situations require ML code to integrate with other infrastructures, like API's, applications, or other websites that require ML code to be correctly configured. We'll configure some crucial production infrastructure for an ML pipeline in this project.

* If ML code is deployed in a way that's not optimal, it can lead to cost overruns or bad performance. We'll choose and deploy optimal computing resources for our ML code in this project.

* When ML code is moved to production deployment, security is always a concern, since poor security can lead to data leaks or performance issues. We'll configure and optimize ML pipeline security in this project.

Our final submission will show our understanding of all of the following aspects of AWS machine learning operations:

1. Managing computing resources efficiently
2. Training models with large datasets using multi-instance training
3. Setting up high-throughput, low-latency pipelines
4. AWS security
5. By improving and preparing an image classification project for production-grade deployment, we'll demonstrate that we have the skills to work on the most advanced ML pipelines in the world. We'll be prepared to do excellent work as an ML engineer with the ability to optimize ML pipelines for efficiency, speed, and security.

## Project Summary
In this project, We will complete the following steps:

1. Train and deploy a model on Sagemaker, using the most appropriate instances. Set up multi-instance training in your Sagemaker notebook.
2. Adjust our Sagemaker notebooks to perform training and deployment on EC2.
3. Set up a Lambda function for our deployed model. Set up auto-scaling for our deployed endpoint as well as concurrency for your Lambda function.
4. Ensure that the security on our ML pipeline is set up properly.
