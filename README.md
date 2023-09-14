# Deployment 1 Documentation
## Purpose
The purpose of deployment 2 was to familiarize ourselves with using Jenkins and AWS Elastic Beanstalk.

## Steps:
1. Before starting working on this deployment, we need to download this repository from Kura Labs and upload it to my GitHub
2. Then, we were credentials to the instructor Jenkins servers. Once we were able to get into the Jenkins server we would have to set up credentials that would allow Jenkins to access my Github repository.
3. Once, Jenkins is able to establish a connection then we will be able to build.
4. After I confirmed that Jenkins was able to build and test the application, we would upload that to AWS Elastic Beanstalk

## System Design Diagram:
To view the System Design Diagram, click [here](https://github.com/auzhangLABS/C4_deployment1/blob/main/diagram.png)

## Issues/ Troubleshooting:
The main issue, I had was uploading the zip file to AWS Elastic Beanstalk, I kept getting an error stating that my health was degraded. Upon investigating, I found out that the source bundle must be compressed without the parent folder. This would ensure that it won't include an extra top-level directory. To fix this, I would extract the zip files and then go into the folder and zip files/folder within that folder.

## Optimization:
I would optimize this deployment by adding a stage into the Jenkins file it would allow Jenkins to zip the file. From there, I would SCP the zip file to my computer and then upload that to AWS Elastic Beanstalk. This way, we won't run into issues with the parent folder and top-level directory.
