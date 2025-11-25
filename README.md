# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web app development and AWS CI/CD tools!

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Contact](#contact)
- [Conclusion](#conclusion)

<br>

## Introduction
This project is used for an introduction to creating and deploying a Java-based web app using AWS, especially CI/CD tools.

The deployment pipeline I am building around the Java web app in this repository is invisible to the end-user, but makes a big impact by automating the software release processes.

- I am taking on this project gain more knowledge about CI/CD as well as hands on experience in automating workflow from developing code to deployed web app.

- This fits into my career goals because I want to work as DevOps engineer this year or at the latest early next year.

<br>

## Technologies
Here's what I'm using for this project:

- **Amazon EC2**: I'm deploying a web app on Amazon EC2 server, so that development and deployment takes place on the cloud.
- **VSCode**: For IDE, I chose Visual Studio Code. It connects to  EC2 instance for development, which makes it easy to edit and manage files in the cloud.
- **GitHub**: All the web app code is stored and versioned in a GitHub repository.
- **AWS CodeArtifact**: Once rolled out, artifacts and dependencies are stored on CodeArtifact. For the purpose high availability and speed up of the project's build process.
- **AWS CodeBuild**:CodeBuild takes over the build process after roll out, it will complete the source code, run tests and produce ready-to-deploy software packages automatically.
- **AWS CodeDeploy**: CodeDeploy will automate deployment process across EC2 instances.
- **AWS CodePipline**: CodePipline will automate the entire process from GitHub to CodeDeploy, integrating build, test and deployment steps into one efficient workflow.


<br>

## Setup
To get this project up and running on local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Adeitan-Abdulfattah/nextwork-web-project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd nextwork-web-project
    ```
3. Install dependencies:
    ```bash
    mvn isntall
    ```

    <br>

    ## Contact
    If you have any questions or comments about this CI/CD project, please contact: 
    Adeitan - [greatlight24@gmail.com](mailto:greatlight24@gmail.com)

    [Linkedin](www.linkedin.com/in/siraajuddeenabdulfattah)
    
    <br>

## Conclusion
Thank you for exploring this project! I'll continue to build this pipline and apply my learnings to future projects.

A big gratitude to **[Nextwork](https://learn.nextwork.org/app)** for the project guide and support. 