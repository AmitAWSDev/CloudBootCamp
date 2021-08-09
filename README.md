# CloudBootCamp
MultiCloud Practice notes

Google Cloud Platform

#My First GCP Bootcamp challenge AUTOMATION USING PYTHON ON GOOGLE CLOUDIAM SERVICE ACCOUNTS – PART 1

1) Install Python on local machine
2) Install Google SDK on local machine
3) Create new project using cloud console
4) Create new service account using GCloud on google shell
5) Update Serivce account name and description using GCloud on google shell
6) Bind role to the service account using GCloud
7) Add key to the service account
8) Access the Google cloud project using the API key and get list of buckets on the account from local machine
-------------------------------------------------------------------------------------------
# Cloud SDK challenge
--------------------------------------------------------------------------------------------
Display the data in JSON format

# gcloud projects list --format json

project ID, project name and the labels in CSV format 
#gcloud projects list --format="csv(projectId, name, labels)"

create compute resource via cloud SDK
gcloud compute instances create example-instance --image-family=rhel-8 --image-project=rhel-cloud --zone=us-central1-a


--------------------------------------------------------------------------------------------
Git Command
1) git branch -m main master
2) git fetch origin
3) git branch -u origin/master master
4) git remote set-head origin -a
