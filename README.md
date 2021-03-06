# Prediction of jobs submitted to one of Purdue's central computing clusters
This assignment deals with predicting failure of application executions (referred to as “job”) on Purdue ITaP’s central computing cluster. This is data that we have collected, collated, and analyzed as part of a project from the National Science Foundation (NSF) (Computer System Failure Data Repository to Enable Data-Driven Dependability Research,” Proposal No. CNS-1513197). 

For each job, we have data about the resources the job uses and whether the job succeeded or failed. The resources for which we have data are:
1.	Memory
2.	Network
3.	Local IO
4.	Network File System (NFS)

We are releasing the training data, which has about 8% failure data (this is referred to as the “positive class”). You will build Machine Learning models in Python to predict whether a job will fail or not, given the resource usage data. We will evaluate your model on some test data that we are not releasing now and that we will use later at the time of the evaluation. 
