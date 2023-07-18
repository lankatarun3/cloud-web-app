
 
# 1	Introduction 50
The main aim behind the development of this document file is to develop an understanding of cloud technology for the business process. For the completion of the study, Abcodia company is used which is a part of the small and medical scale category. The report contains the strategy for cloud deployment with the consideration of the enterprise background, the Current information technology setup of the company, and recommendations about the cloud and non-cloud solutions.

# 2	Enterprise background 100
The main aim behind the development of this document file is to develop an understanding of cloud technology for the business process. For the completion of the study, Abcodia company is used which is a part of the small and medical scale category. The report contains the strategy for cloud deployment with the consideration of the enterprise background, the Current information technology setup of the company, and recommendations about the cloud and non-cloud solutions.

# 3	Current IT Setup 200
If we talk about the recent setup of the Information technology upgradation of the company then it can be stated that Abcodia is associated with the website that contains the information cancer test which named as ROCA test. Apart from that company is associated with different pages which is helpful for the customers. The company distinguished the website into the different sections which are the patient purpose, clinical purpose, and blog sections. After inspecting the website, we get the information that there is a range of links that are disabled which leads to the weak performance of the website (ROCA Test 2023).

# 4	Deployment Procedure 200
## Setup Directory structure:
The directory structure should be setup as per according to the given image which includes the source code and all the required files along with the Dockerfile to create and containerize the image.
 ![image](https://github.com/lankatarun3/cloud-web-app/assets/133871675/ad4017b0-d6d5-4a92-8262-e1f5f527e6fa)

## Test the code in local:
Run the python file in local to test the code. Copy the URL shown in the image and paste in google to check if the web application is running.
 ![image](https://github.com/lankatarun3/cloud-web-app/assets/133871675/8c661c42-b5b9-4853-a606-8be1f1dfd167)

## Create a Docker image:
In order to containerize the application, we have to create a docker image using the docker commands as shown in the image below.
Once the image is built, we can check the images present in the local using command: 
docker images: - it will display all the images present in the local.
 ![image](https://github.com/lankatarun3/cloud-web-app/assets/133871675/19331dee-ea28-4c5b-94f9-74b5199b33e5)

## Run the Docker image:
Once the Docker image is created, we can run the image using the docker run command as shown in the image.
On running the image, a container is created on which the image will run. Copy the url present in the logs to check the running we application.
 ![image](https://github.com/lankatarun3/cloud-web-app/assets/133871675/87cc7301-27ce-42e3-8fee-9fc63fc39542)

## Docker Desktop:
We can also check the image and the container created in the docker desktop as shown in the below image.
The image is also pushed to docker hub in order to run the web application through the docker desktop.
 ![image](https://github.com/lankatarun3/cloud-web-app/assets/133871675/bf782f04-7400-4a34-b691-4d172ca0b8ae)

## Push the Image and source code to github:
Now the created docker image is pushed to github registry using the below steps:\
•	Login to the github registry using PAT(Personal Access token)\
•	Tag the docker image to the github registry\
•	Push the docker image to the github as shown in the image below.\
•	Verify the image pushed in the github using the github portal.
 ![image](https://github.com/lankatarun3/cloud-web-app/assets/133871675/80e17b55-27b3-4c9a-8af9-f8640d116a16)

## Upload the resource to azure as container:
In order to upload the container application in azure we have to upload the image to the azure container registry by using the commands as shown:
•	Login to the azure using az login\
•	Create the azure container registry using the resource group\
•	Tag the docker image to azure container registry.\
•	Login to azure container registry.\
•	Push the image to azure container registry.\
•	Check the uploaded container resource on the azure container registry.
 
## Web application testing:
The web application which is running on the server mentioned in the logs is as shown in the below images. It depicts the usage of the cloud application or resources by the SME company in order to move the on-premise infrastructure to cloud infrastructure using the deployment of cloud resources or services.

 ![image](https://github.com/lankatarun3/cloud-web-app/assets/133871675/82b64071-7a48-4d83-a0d2-4460e591102d)

 
 
# 5	Recommendations 400
5.1	Cloud vs non-cloud solutions
## Cloud Solutions:
•	Cloud solutions involve deploying, hosting the applications on the remote server or using the remote database to store the data.\
•	Using cloud we can scale up or scale down the applications based on our requirements in order to save the cost and maintain the speed.\
•	Using cloud anyone can access the remote server without much more dependency on the on-premise infrastructure.\
## Non-Cloud Solutions:
•	Non-Cloud solutions involve deploying, hosting the applications on the On-Premise infrastructure.\
•	We have greater control of infrastructure in the non-cloud as we can maintain and update the infrastructure as per our needs.\
## 5.2	Appropriate deployment types and service level
For deploying the cloud resources or services we needed.\
•	Docker instance\
•	Docker Container\
•	Github Registry\
•	Containerize the application\
•	Updating the application.\
•	Multi-Container Apps
Services/Resources used:\
•	Azure Active registry\
•	Github Registry\
•	Docker Desktop\
•	Python/HTML/CSS/JS
# 5.3	Justification for Recommendation
The traditional on-premise infrastructure basically known as non-Cloud solutions involve deploying, hosting the applications on the On-Premise infrastructure. We are not able to scale up or scale down based on the demands. 
We don’t get the flexibility to use the remote access of the servers. Also, it requires the high infrastructure costs for the setup. The deployment of the resources and services take more time and it’s not fully automated.
Considering all these conditions for the organization which requires scalability, less infrastructure costs and remote access to the resources it is necessary to move from on-premise to the cloud environment which includes moving of the on-premise system to the cloud resources and to use the containerization to host the application on the remote server or by using the virtual machine on the cloud server.

## 6	Conclusion
It can be stated that this document is the perfect reflection of the entire progress of cloud deployment. In order to complete the research, we developed a web application and then push it into the docker and GitHub. After that, the application is also deployed on Azure that contains the different resources.

## 7	References
Azure. (2023). Data Privacy in the Trusted Cloud. Microsoft Azure. [online] Available at: https://azure.microsoft.com/en-in/explore/trusted-cloud/privacy [Accessed 10 Jul. 2023].\
Crunchbase. (2022). Crunchbase. [online] Available at: https://www.crunchbase.com/organization/abcodia [Accessed 10 Jul. 2023].\
IBM. (2023). What is a Cloud Server. [online] Available at: https://www.ibm.com/topics/cloud-server [Accessed 10 Jul. 2023].\
ROCA Test. (2023). Contact Us for Assistance. [online] Available at: https://www.therocatest.co.uk/contact-us/ [Accessed 10 Jul. 2023].


