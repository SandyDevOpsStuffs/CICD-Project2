Task: Implement a CI/CD Pipeline with GitHub Actions for Automated Deployment and Rollback
Problem Statement: Configure a GitHub Actions workflow to automate the deployment of simple web application on github to AWS ECS (Elastic Container Service). The pipeline should include deployment, integration tests, and rollback functionality. With following steps
1.	Checkout code from github repository
2.	Build optimize docker image with multistage build to serve with nginx as reverse proxy.
3.	Push image to ECR
4.	Deploy on ECS.
5.	Perform Integration tests and rollback functionality in case of failure.

Please run the CI/CD pipeline on your end and submit snapshots of each job and step from the GitHub Actions pipeline. Along with these snapshots, include the URL to your GitHub repository. Note that both the successful execution of the pipeline and the quality of code documentation are crucial for this assessment. Ensure that your repository has a well-written README file explaining the setup, usage, and testing of the pipeline and any other relevant details.
