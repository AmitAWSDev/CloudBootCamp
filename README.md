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

1) gcloud projects list --format json

project ID, project name and the labels in CSV format 
1) gcloud projects list --format="csv(projectId, name, labels)"

create compute resource via cloud SDK

1) gcloud compute instances create vm1 --zone=us-west1-b

if you want to see help please use below command

2) gcloud compute instances create --help

create farewall rule
1) gcloud compute firewall-rules create allow-80 --allow tcp:80

connect to ssh
1) gcloud compute ssh vm1
2) install nginx on ssh window
   a) sudo su - 
   b) apt-get update
   c) apt-get install -y wget
   d) apt-get install -y nginx
   e) service nginx start
   f) exit
   g) wget -q -O - localhost:80 | grep nginx
   
   Verify via UI 
   externalip:80



--------------------------------------------------------------------------------------------
Git Command
1) git branch -m main master
2) git fetch origin
3) git branch -u origin/master master
4) git remote set-head origin -a
