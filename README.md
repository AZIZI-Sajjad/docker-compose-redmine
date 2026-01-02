# redmine-docker
Container base redmine with mysql

### How to use : 
```
# 1- Clone the project  
https://github.com/AZIZI-Sajjad/docker-compose-redmine.git

# 2- Go to project's root Directory  
cd docker-compose-redmine

# 3- Define Vriables in .env  
nano -c .env

# 4- create Volumes' folder:  
mkdir redmine && mkdir mysql

# 4- run the docker compose project :
# docker compose --file ./docker-compose.yml --project-name redmine-project config
# docker compose --file ./docker-compose.yml --project-name redmine-project up
# docker compose --file ./docker-compose.yml --project-name redmine-project down
# docker compose --file ./docker-compose.yml --project-name redmine-project logs -f

# Open navigator : 
http://<Docker_Host_IP>:8026/redmine
```


