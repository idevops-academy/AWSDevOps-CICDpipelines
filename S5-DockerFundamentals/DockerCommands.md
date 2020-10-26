# Docker Fundamentals

## 1. Pull Container Image
Syntax:
```
docker pull imagename:version
```
Examples: 

| Action        | Command       | 
|-------------  | ------------- |
|get latest version| ```docker pull shaik447/mapapp``` |
|get specific version| ```docker pull shaik447/mapapp:1.0``` |

## 2. Run Containers
Syntax:
```
docker run [options] imagename:version
```
Examples: 

| Action        | Command       | 
|-------------  | ------------- |
|run in foreground| ```docker run shaik447/mapapp``` |
|run in background| ```docker run -d shaik447/mapapp``` |
|port mapping with host| ```docker run -d -p 80:80 shaik447/mapapp``` |
