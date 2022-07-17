# udacity-devops-course-project-2
My implementation of project 2 (Deploy a High-Availability Web App using Cloudformation) in Udacity's Cloud-Devops


## How to run/deploy [Steps in order]
1.  ```./create.sh network-stack network.yml network-params.json```
2.  ```./create.sh server-stack servers.yml servers-params.json```
3.  ```./create.sh jumpbox-stack jumpbox.yml jumpbox-params.json```
