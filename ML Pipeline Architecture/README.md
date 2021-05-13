## Ideas and resources to architect a Scalable ML Application in Production

### Only a small fraction of a real-world ML system is composed of the ML code. The required surrounding elements are vast and complex.
![alt text](https://cloud.google.com/architecture/images/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning-1-elements-of-ml.png)



### MLOps level 0: Manual process - Manual ML steps to serve the model as a prediction service.
![alt text](https://cloud.google.com/architecture/images/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning-2-manual-ml.svg)



### MLOps level 1: ML pipeline automation - ML pipeline automation for CT
![alt text](https://cloud.google.com/architecture/images/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning-3-ml-automation-ct.svg)



### MLOps level 2: CI/CD pipeline automation - CI/CD and automated ML pipeline
![alt text](https://cloud.google.com/architecture/images/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning-4-ml-automation-ci-cd.svg)



This MLOps setup includes the following components:
- Source control
- Test and build services
- Deployment services
- Model registry
- Feature store
- ML metadata store
- ML pipeline orchestrator



#### Stages of the ML CI/CD automation pipeline:
![alt text](https://cloud.google.com/architecture/images/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning-5-stages.svg)


### MLOps architecture by neptune.ai:
![alt text](https://i1.wp.com/neptune.ai/wp-content/uploads/Metadata-store.jpg?ssl=1)

![alt text](https://miro.medium.com/max/7912/1*Bt1PVhREAdFLUZeGYB8eSQ.jpeg)


Ref: 
- https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning
- https://towardsdatascience.com/architecting-a-machine-learning-pipeline-a847f094d1c7
- https://neptune.ai/product

