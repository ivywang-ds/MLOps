---
description: >-
  This article delves into the intricacies of machine learning deployment,
  covering its various types, deployment steps, considerations for selecting a
  deployment environment, and the role of configurat
---

# Deployment

Once a model has been trained and evaluated to the desired level of accuracy, the next step is to deploy it into a production environment where it can be used to make real-world predictions or decisions. Deployment is a critical phase in the machine learning lifecycle, as it ensures that the model can be accessed and integrated with the application workflow seamlessly.&#x20;

### Inference Types

Machine learning models can be deployed for two primary types of inference:

**Real-time inference** involves processing data and producing predictions as quickly as possible. This type of inference is typically used for applications that require immediate responses to user requests or events. For example, real-time inference is used in personalized product recommendations, advertisement allocations, and fraud detection in online transactions.

**Batch inference** involves processing large amounts of data offline and producing predictions at a later time. This type of inference is typically used for applications that require less immediate responses or that can handle delayed predictions. For example, batch inference is used in risk analysis, where the model can be trained on historical data and then used to make multiple predictions at one time on new data.



### Deployment Steps

The deployment process for machine learning models typically involves the following steps:

1. **Model packaging:** The model, its dependencies, and any necessary configuration files are encapsulated into a deployable format. This format can vary depending on the deployment environment, but common formats include PMML, ONNX, and TensorFlow SavedModels.
2. **Infrastructure provisioning:** The necessary infrastructure, such as servers, databases, and containers, is provisioned to host the deployed model. This may involve setting up clusters of machines, configuring network connectivity, and installing the necessary software.
3. **Model serving:** The model is deployed to the production environment and integrated with the application's workflow. This involves configuring the application to send data to the model for predictions, receiving the predictions from the model, and incorporating the predictions into the application's decision-making process.
4. **Configuration management:** The deployment process is automated to ensure consistency and reliability. This may involve using tools like Docker, Kubernetes, or cloud-native deployment platforms to automate the deployment and management of the model and its infrastructure.



### Deployment Types

There are several different types of deployment environments for machine learning models, each with its own advantages and disadvantages. The choice of deployment environment depends on the specific requirements of the application, such as latency requirements, data volume, and security considerations.

**On-premises deployment:** Machine learning models are deployed on a local server or network within the organization's own infrastructure. This provides tight control over data security and privacy, as well as the ability to tailor the deployment environment to specific needs. However, it requires maintaining and managing the infrastructure, which can be resource-intensive and complex.

**Cloud deployment:** Machine learning models are deployed on a public cloud platform such as AWS, Azure, or Google Cloud. This offers scalability, flexibility, and cost-effective resource provisioning. However, it involves entrusting data and model management to the cloud provider and adhering to their terms of service.

**Mobile deployment:** Machine learning models are embedded into mobile applications. This is suitable for real-time applications that require low latency and on-device processing, such as image recognition or natural language processing within mobile apps.

**Edge deployment:** Machine learning models are deployed on edge devices, such as routers, sensors, or IoT devices, close to the data source. This is suitable for applications that require ultra-low latency and real-time decision-making, such as autonomous vehicles or industrial IoT applications.

