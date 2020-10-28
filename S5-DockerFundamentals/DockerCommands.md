# Docker Fundamentals

## 1. Pull Container Image
Syntax:
```
docker pull imagename:version
```
Examples: 

| Action        | Command       | 
|-------------  | ------------- |
|get latest version| ```docker pull idevops47/mapapp``` |
|get specific version| ```docker pull idevops47/mapapp:1.0``` |

## 2. Run Containers
Syntax:
```
docker run [options] imagename:version
```
Examples: 

| Action        | Command       | 
|-------------  | ------------- |
|run in foreground| ```docker run idevops47/mapapp``` |
|run in background| ```docker run -d idevops47/mapapp``` |
|port mapping with host| ```docker run -d -p 80:80 idevops47/mapapp``` |




Container Management - logs 'logs follow' exec 'exec with -it' stop ps -a start 'rm rm -f' restart policy env cp top 

1. see logs - docker logs firstmap
2. see the last 10 lines - docker logs firstmap --tail 10
3. follow logs - docker logs firstmap --follow
4. exec ls to show root directories
5. exec mkdir tmp2 - create directory and exec ls again to show the folder
6. exec it firstmap bash - to go inside the terminal
7. Stop container by name
8. ps -a
9. start by id
10. show rm and then use rm -f
11. restart policy?
12. cp file to /tmp
13. docker top
14. docker attach
15. pass --env dburl=myurl , exec containername env to list env 
15. -f name=sss , -f name =sss -f name = ddd
15. docker ps -q , ps -aq, rm -f $(ps -aq)
14. other imp commands: restart policy?



Image management - images rmi commit tag login push history
Image management - create image Dockerfile

Volumes

Network



