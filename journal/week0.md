# Week 0 — Billing and Architecture
# Chapter 1: Hoisting the Jolly Roger of Cloud Security - Bootcamp Format & Conceptual Design Quest
https://www.youtube.com/live/SG8blanhAOg?si=2m-bKkUDKWubbVkm

Here, I went through the format of the bootcamp and the business usecase of the project. Apart from this, I also went through the architectural diagram of what we plan to build and how to use Lucid Charts to build architectures. 
Also got intoduced to various models like C4 models. This video also talked about how to build a good architecture by gathering your RRAC's: 
* Requirements
* Risks
* Assumptions
* Contraints

Once the RRAC's have been gathered, you can create a Conceptual design, Logical design and then a Physical design. (I used ChatGPT for these concise explanations.)

* Conceptual design: Think of it as the blueprint of dreams, where concepts take shape, unfettered by practicality. It's about answering "What could it be?" rather than "How will it be?" In other words,  it's the creative phase where you define the app's purpose, target audience, and the problem it will solve. You might create rough sketches, brainstorm features, and explore the app's unique selling points (USPs). At this stage, you're answering questions like "What problem will my app solve?" and "What should the user experience be like?" It's about defining the app's high-level concept and vision.
* Logical design:  Imagine it as a well-structured novel outline, where characters, plots, and themes are carefully defined. In logical design, abstract concepts are translated into a structured plan, but the specifics of implementation are not yet addressed. It involves translating your app concept into a structured plan. You create wireframes or mockups that outline the app's user interface (UI) and user experience (UX). You define the app's data flow, functionalities, and how different components will interact. This phase is about answering "How will my app work?" and "What features and functionalities will it have?" Logical design ensures that the app's architecture and user flow make sense without delving into the technical specifics.
* Physical design: Physical design is about practical implementation, turning ideas into tangible reality.  It's about turning the logical design into actual code and creating a working prototype or a fully functional app. Here, developers write the actual software, design the database, integrate third-party services, and handle the technical aspects. Physical design answers questions like "What technologies will we use?" and "How will we build and deploy the app?" It's the practical implementation phase.

Here is the Conceptual design for the Cruddur app: https://lucid.app/lucidchart/0d05c807-c57f-40a6-919e-94e41262a5b7/edit?viewport_loc=-1118%2C-414%2C2220%2C946%2C0_0&invitationId=inv_72456583-0124-449d-a7b8-49f92c6cf5ef

![Cruddur - Conceptual Diagram](https://github.com/stygian14/aws-bootcamp-cruddur-2023/assets/69624766/f0863b9f-1354-41de-bae2-fe4d0551a895)
# Chapter 2: Treasure Allocation: Navigating the Cloud Sea of Expenditure -  Spend Considerations $$$$
https://youtu.be/OVw3RrlP-sI

Here, I went through the billing part in the AWS console. Activated the Invoice delivery preferences to be sent to my root email address and Alert preferences for AWS Free Tier delivered to my root email address.

# Chapter 3: Cipher Pol Chronicles: Navigating Security Waters - Security Considerations

https://youtu.be/4EMWBYVggQI?si=FhxWFkPtKSVD0aKn 

The introductory (week 0) related security considerations were given, starting with what cloud security is and why is it even needed followed by week 0 day 0 security considerations:  
*What is Cloud Security?*
Cybersecurity that protects the data, applications, and services associated with Cloud environments from both external and internal security threats.
*Why care about Cloud Security?*
Reducing impact of breach protecting networks, applications, services in cloud environments against malicious data theft and reducing the human error responsible for data leaks
I went through the  steps: 

- *Step 1: Add MFA to root user.* 
- *Step 2: Create an organization unit.*
- *Step 3: Enable AWS cloud trail.*
- *Step 4: Create IAM users.*
- *Step 5: Create AWS IAM roles.*
- *Step 6: Enable AWS Organization SCP*
# Chapter 4: Poneglyph Prowess: Charting the Cloud with Lucid Charts: Conceptual Diagram in Lucid Charts
