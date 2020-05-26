git pull https://github.com/esboych/windows-rds-terraform.git

terraform fmt
terraform init
terraform plan
terraform apply

gcloud compute reset-windows-password vm-bastionhost --user app_admin --zone us-central1-a

gcloud compute reset-windows-password vm-securehost --user app --zone us-central1-a