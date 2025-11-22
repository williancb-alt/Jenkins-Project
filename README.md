This project demonstrates the creation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins, Docker, and GitHub to automate the process of building, testing, and deploying application code. By integrating Jenkins Pipeline scripts with GitHub repositories, the setup enables automatic code synchronization and execution of build tasks on Docker-based cloud nodes. The pipeline is configured to poll GitHub every five minutes for new changes, triggering automated workflows that minimize the need for manual intervention and streamline collaborative software delivery efforts.

#Project Purpose:
Deploy a simple CI/CD pipeline using Jenkins, Docker, and GitHub to automate code integration and deployment.

#Documentation:
Full project documentation provided (delivered to Maria) explaining setup, configuration, and usage.

#Pipeline Management:
Uses Jenkins Pipeline scripts managed through Source Code Management (SCM).

#GitHub Integration:
The pipeline pulls source code from a GitHub repository, enabling automatic synchronization with the latest changes.

#Automation:
Jenkins automates the build, test, and deployment processes using cloud-based Docker nodes as build agents.

#Polling Mechanism:
Jenkins is configured to poll GitHub every 5 minutes for code changes using the "Trigger Poll SCM" feature.

#Triggering Pipeline Runs:
On detecting code updates, Jenkins triggers pipeline runs that execute the necessary commands to update and deploy the application.

#Minimal Manual Intervention:
The automation minimizes manual interactions with other teams and speeds up the development lifecycle.

#Benefits:
*Ensures continuous integration and delivery of updated code
*Improves deployment speed and reliability
*Provides scalability and isolation via Docker-based Jenkins agents
*Supports collaborative and efficient development workflows
 


