# AWS CI/CD Pipeline
This AWS CI/CD pipeline script automates the deployment of a sample website using AWS CodePipeline and related services.

# Prerequisites
Before running this pipeline, make sure you have the following prerequisites:

- An AWS account
The sample website code ready for deployment
Pipeline Overview
This AWS CI/CD pipeline consists of the following phases:

# Phase: Install
This phase installs Nginx on the target system.

# Phase: Pre-Build
This phase performs pre-build tasks.

# Phase: Build
This phase deploys the sample website by copying the files to the /var/www/html directory and creating a zip file of the website.

# Phase: Post-Build
This phase performs post-build tasks.

Usage
- To use this AWS CI/CD pipeline, follow these steps:

- Set up an AWS CodePipeline and related services.

- Configure the pipeline with the necessary parameters:

- Source: Specify the source location of the sample website code.

- Destination: Define the destination directory where the files will be deployed (e.g., /var/www/html).
- Set up the required hooks and specify the scripts to run after installation and application start.

Save the pipeline configuration and trigger the deployment.

Contributing
If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request to this repository.

License
This project is licensed under the MIT License.

Feel free to customize this README file based on your specific AWS CI/CD pipeline configuration and deployment process.# 

<img width="960" alt="mysuccess" src="https://github.com/Simrankhott/aws/assets/91006102/b8bb238b-4c02-4b03-9bee-0205362b7baa">
