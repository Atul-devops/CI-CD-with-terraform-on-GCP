# CI-CD-with-terraform-on-GCP

Deploy the CI/CD using Terraform

Following steps will create resources in GCP project

Google Cloud Repository
Google Cloud Build
Google Cloud Container Registry
Google Cloud Run

Create Project

Create SA, Assign the roles: Editor, Security Admin, Service Usage Consumer, Source Repository Administrator and download key as terraform.json

export GOOGLE_CLOUD_KEYFILE_JSON=terraform-key.json
git clone  ------
cd  -----
terraform init
terraform plan
terraform apply

Following steps to push the code into CSR

cd to root
cd..

set remote

git remote add google https://source.developers.google.com/p/[PROJECT_ID]/r/[REPO_NAME]

Push the code

git push --all google
