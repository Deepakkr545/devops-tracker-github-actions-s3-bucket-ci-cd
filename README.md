
**DevOps Learning Tracker Static Website CI/CD with GitHub Actions and S3**

This project demonstrates a Continuous Integration and Continuous Deployment (CI/CD) pipeline for a static DevOps learning tracker web application hosted on AWS S3. It uses GitHub Actions to automatically build and deploy the latest changes from the repository to an S3 bucket whenever a commit is pushed to the main branch.

### Key Features:

* Interactive static website built using HTML, CSS, and JavaScript for tracking DevOps topics.
* GitHub Actions workflow defined in a `.yml` file for automated deployment.
* AWS credentials securely stored using GitHub Secrets.
* Changes pushed to GitHub are automatically synced to the S3 bucket.
* S3 bucket configured to host a static website.

### Technologies Used:

* GitHub Actions (CI/CD automation)
* AWS S3 (Static website hosting)
* AWS IAM (Programmatic access with least privilege)
* GitHub Secrets (Secure storage of AWS credentials)

### How it Works:

1. Code is pushed to the main branch.
2. GitHub Actions triggers the workflow.
3. The workflow:

   * Configures AWS credentials.
   * Syncs files to the S3 bucket using the AWS CLI.
4. The S3 bucket serves the latest version of the DevOps learning tracker website.

---

If you want, I can also help you draft a README file with this description!
