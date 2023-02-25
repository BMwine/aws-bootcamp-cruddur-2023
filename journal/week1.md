# Week 1 — App Containerization

## Docker and App Containerization

### Technical Tasks Completed:

1. Containerized the backend app

![Containerized the Backend App](https://user-images.githubusercontent.com/28305009/221349898-5bea5f43-cf5b-422e-a54e-bf5a80d786c7.PNG)


1. Write a Dockerfile for each app

![Both Dockerfiles](https://user-images.githubusercontent.com/28305009/221354637-af4a23bb-7fdc-4304-9b69-0bd2bc76cf75.PNG)

1. Ensure we get the apps running via individual container





1. Create a docker-compose file


Ensure we can orchestrate multiple containers to run side by side


Business Scenario
Your company has received the code repositories for the demo application from the contracted web-development firm. The company wants you to investigate the codebases, and ensure you can get them running.

The fractional CTO has suggested we first begin containerizing the applications for both developer and production use, and their reasons stayed why:
To avoid lack of documentation of application and OS configuration
To ensure the effort of application and OS configuration is factored in before investing lots of feature development
If we decide to hire our technical team members we can quickly replicate these environments in any preferred choice.

The fractional CTO has asked that everything be developed in Gitpod, (a Cloud Developer Environment). This will allow the CTO at a press of a button launch the developer environment in a clean state to help with any tricky or emergency implementations, and ensure developer accountability.

Gitpod was since it supports multiple Version Control Services (VCS).. The company has invested considerable effort already in Atlassian JIRA working with the web-dev firm, and repo’s highly likely might be moved to Atlassian BitBucket to take advantage of better integrations within the Atlassian’s ecosystem. 

Weekly Outcome
Gain practical knowledge working with common docker command and running container images for the purpose of local development

![image](https://user-images.githubusercontent.com/28305009/221352888-2994dadf-1652-47af-a679-f5181c3b6792.png)

Gain practical knowledge of working within a Cloud Development environment
Be able to navigate a backend and front web-application and generally understand how they work 

Possible Spend Considerations
Detail GitHub free-tier
Detail Gitpod free-tier

Alternatives and Considerations
…

Security Considerations
…

 Homework Challenges    
Run the dockerfile CMD as an external script
Push and tag a image to DockerHub (they have a free tier)
Use multi-stage building for a Dockerfile build
Implement a healthcheck in the V3 Docker compose file
Research best practices of Dockerfiles and attempt to implement it in your Dockerfile
Learn how to install Docker on your localmachine and get the same containers running outside of Gitpod / Codespaces
Launch an EC2 instance that has docker installed, and pull a container to demonstrate you can run your own docker processes. 



Technical Tasks	20
Business Scenario	20
Weekly Outcome	21
Possible Spend Considerations	21
Alternatives and Considerations	21
Security Considerations	21
Homework Challenges
