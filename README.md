---

# Cloud Resume Website S3 Bucket

This Amazon S3 bucket is a part of a larger project and hosts the HTML files for my resume website. It also includes the necessary configuration files for automated deployment using GitHub Actions.

## Contents

- **HTML Files**: The `index.html` files contain the content of my resume website.
- **IAM Policy**: The `githubactions_role_iam.json` file contains the IAM policy that allows GitHub Actions to push changes to this S3 bucket using OIDC (OpenID Connect).
- **GitHub Actions Workflow**: The `.github/workflows/main.yml` file contains the GitHub Actions workflow configuration. It assumes the GitHub Actions role to perform deployment tasks.

## Deployment

The website is automatically updated whenever changes are committed to the main branch of the associated GitHub repository. GitHub Actions trigger the deployment workflow, which pushes the updated HTML files to this S3 bucket.

---

This version focuses on the S3 bucket as a part of a larger project.
