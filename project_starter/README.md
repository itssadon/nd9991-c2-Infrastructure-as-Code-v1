# Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:

#### final-project-network.yaml
I wrote the CloudFormation code using this YAML template for building the network for the cloud infrastructure, as required for the project.

#### final-project-network-parameters.json
I used a JSON file for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject".

#### final-project-server.yml
I wrote the CloudFormation code using this YAML template for building the cloud infrastructure, as required for the project. 

#### final-project-server-parameters.json
I used this JSON file to increase the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject". 

#### final-project-jump-server.yml
I wrote the CloudFormation code using this YAML template for building the cloud infrastructure, as required for the project. 

#### final-project-jump-server-parameters.json
I used this JSON file to increase the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject". 

#### website.zip
I wrote the index file to be displayed on the autoscalled instances. 

In YAML code, the `${EnvironmentName}` would be substituted with `UdacityProject` accordingly.

#### ALB DNS
[Website URL](http://udaci-webap-11s8tcd24ipwz-196704047.us-east-1.elb.amazonaws.com/)

## Reference materials
- [AWS CLoudFormation User guide](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)
- [Ubuntu Cloud Image Finder](https://cloud-images.ubuntu.com/locator/)