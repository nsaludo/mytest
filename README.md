# CSCI E91 FInal Project
----
## Silver Team
#### James Fulford
#### Mengying Wang
#### Nora Saludo
----
This is to showcase the CI/CD techniques to enable DevOps teams to deploy software rapidly, repeatedly, and reliably. In this project, we will build a pipeline to serve a website that needs a seamless, end-to-end continuous delivery and deployment workflow: from source code, to build, to deployment, to software delivery. <sup>e91_FinalProject.pdf Harvard University Extension School CSCIE9</sup>

### Contents
* terraform - terraform templates and user data to create the Ansible Server and the productiosn serve on Google Cloud
* ansible - ansible playbook files to install Jenkins on the Jenkins Service in AWS
* cloudformation - templates for Jenkins Srever, Dev and Staging Server used in AWS Cloudformation 
* jenkins - pipeline groovy script used in setting up pipeline in jenkins
----
![CI-CD Diagram](/images/cscie91-finals-diagram.png)
