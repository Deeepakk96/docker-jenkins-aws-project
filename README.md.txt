Automated Web Application Deployment using DevOps Pipeline 

Project Overview 
This project showcases an end-to-end CI/CD automation pipeline to build and deploy a static web 
application using GitHub, Jenkins, and Docker on AWS infrastructure. 

Tools & Technologies 
• Git & GitHub 
• Jenkins 
• Docker 
• AWS EC2 
• Nginx (Web Server) 

Project Workflow 
Step 1: Application Development 

Developed a basic static web application using HTML. 

Step 2: Version Control Setup 

Initialized a Git repository and pushed the application code to GitHub for version management. 

Step 3: Containerization 

Create a Docker file using the Nginx base image to package the application into a container. 

Step 4: Jenkins Configuration 

Installed and configured Jenkins on AWS EC2. Integrated GitHub repository and installed required 
plugins (Git & Docker). 

Step 5: CI/CD Pipeline Execution 

• Pulled latest code from GitHub 
• Built Docker image automatically 
• Deployed application using Docker container 



Step 6: Deployment on Cloud 

Successfully deployed the application on AWS EC2 and accessed it via public IP address. 

 Final Output 
The web application was deployed successfully using an automated CI/CD pipeline, reducing manual 
effort and improving deployment efficiency.