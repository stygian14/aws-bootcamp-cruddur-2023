# Week 1 — App Containerization

# Chapter 1: Setting Sail with Containers - Docker Containerization
Here, I went through the basics of what docker is and it's use. Followed through the video in order to get the frontend and backend images.

This is the result I got with the backend image running and adding the api/activities/home in the url.
![1 docker](https://github.com/stygian14/aws-bootcamp-cruddur-2023/assets/69624766/04ee953c-36a7-4503-ad13-a76738ead8cb)

This shows that the back-end flask image is created.
![2 docker img](https://github.com/stygian14/aws-bootcamp-cruddur-2023/assets/69624766/183c4e21-ec47-423d-9184-36948fe8fb76)

This is the result I got after running the docker-compose file. (result from the frontend url)
![3 docker front end](https://github.com/stygian14/aws-bootcamp-cruddur-2023/assets/69624766/2f023916-a1f4-47bb-ae55-edd2338a1b8f)

# Chapter 2: The Pirate's Code of Version Control - Remember to Commit Your Code
Commit the code in github from gitpod and sync it.

# Chapter 3: Managing Your Bounty Wisely - Spending Considerations
Here, I went through the pricing for Gitpod, GitHub Codespaces, AWS Cloud9 and CloudTrail.

# Chapter 4: Guarding Your Treasure Chest - Container Security Considerations
Here, I went through various security considerations for containers. Also, got to know about various security practices and services like Snyk, AWS Secret Manager, HashiCorp Vault etc.

*What is Container Security?*
*Container Security is the practice of protecting your applications hosted on compute services like Containers. Common examples of applications can be Single Page Applications (SPAs), Microservices, APIs etc.*

*Why care about container security?*
- *Container First Strategy.*
- *Most applications are being developed with Containers and Cloud Native.*
- *Reducing impact of breach- segregation of application(s) & related services.*
- *Managed Container services means your security responsibility is focussed on few things (AWS ECS, AWS ECR)*
- *Automation can reduce recovery times and in known good state fairly easy.*

These are the Container Security Components: (there's many more but these are for week 1 so that nobody's overwhelmed!
- Docker & Host Configuration
- Securing Images
- Secret Management
- Application Security
- Data Security
- Monitoring Containers
- Compliance Framework

Top 10 security best practices:
- Keep Host & Docker Updated to latest security Patches
- Docker daemon & containers should run in non-root user mode
- Image Vulnerability Scanning
- Trusting a Private vs Public Image Registry
- No Sensitive Data in Docker files or Images
- Use Secret Management Services to Share secrets
- Read only File system and Volume for Docker
- Separate databases for long term storage
- Use DevSecOps practices while building application security
- Ensure all Code is tested for vulnerabilities before production use



# Chapter 5: Crafting Your Ship - Containerize Application (Dockerfiles, Docker Compose)

Followed through the video in order to get the frontend and backend images.

This is the result I got with the backend image running and adding the api/activities/home in the url.
![1 docker](https://github.com/stygian14/aws-bootcamp-cruddur-2023/assets/69624766/04ee953c-36a7-4503-ad13-a76738ead8cb)

This shows that the back-end flask image is created.
![2 docker img](https://github.com/stygian14/aws-bootcamp-cruddur-2023/assets/69624766/183c4e21-ec47-423d-9184-36948fe8fb76)

This is the result I got after running the docker-compose file. (result from the frontend url)
![3 docker front end](https://github.com/stygian14/aws-bootcamp-cruddur-2023/assets/69624766/2f023916-a1f4-47bb-ae55-edd2338a1b8f)


# Chapter 6: Unveiling the Ancient Scrolls - Document the Notification Endpoint for the OpenAI Document

# Chapter 7: A Pirate's Journal - Write a React Page for Notifications


# Chapter 8: The Navigator's Guide - Write a Flask Backend Endpoint for Notifications
![3 docker front end](https://github.com/stygian14/aws-bootcamp-cruddur-2023/assets/69624766/9b15f74d-f7f3-43e9-8059-785b27fb5caa)
![4 open api backend](https://github.com/stygian14/aws-bootcamp-cruddur-2023/assets/69624766/35371f75-6735-4d7a-80f8-ff0fac5bbdb8)
![5 open api frontend](https://github.com/stygian14/aws-bootcamp-cruddur-2023/assets/69624766/8996664c-abf7-4c8a-9bc7-b584ecd54290)



# Chapter 9: Harnessing the Power of Thunder - Run DynamoDB Local Container and ensure it works

# Chapter 10: The Treasure Vault's Keeper - Run Postgres Container and ensure it works

# Chapter 11: 

