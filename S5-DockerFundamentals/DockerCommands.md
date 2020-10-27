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




logs 'logs follow' exec 'exec with -it' stop ps -a start 'rm rm -f'  