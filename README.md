# gcloud-functions

- Authenticate gcloud CLI locally
- Create new project 
gcloud projects create PROJECT_ID --name="My App"
- Set the project ID
gcloud config set project PROJECT_ID
- # List billing accounts available
gcloud beta billing accounts list

# Link a billing account to project
gcloud beta billing projects link PROJECT_ID --billing-account=BILLING_ACCOUNT_I
