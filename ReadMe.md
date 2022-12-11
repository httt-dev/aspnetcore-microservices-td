## AspnetCore Microservices Tutorial

## Chuan bi moi truong 
* Install dotnet core version in the file `global.json`
* Visual studio CE 2022+

## How to run project

Run command for build project 

```powershell
dotnet build
```
Goto folder contain file `docker-compose`

1. Using docker-compose

```Powershell

docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d --remove-orphans

```
## Application URLs - LOCAL enviroment ( Docker container)

## Docker Application URLs -LOCAL enviroment ( Docker Container)

- Portainer : http://localhost:9000 - user : admin / pass : Abc12345
- Kibana : http://localhost:5601 - user : admin / pass : Abc12345
- RabbitMQ : http://localhost:15672 - user : admin / pass : Abc12345

2. Using Visual Studio 2022
- Open aspnetcore-microservices-td\aspnetcore-microservices.sln
- Run compound to start multi projects

## Application URLs - DEVELOPMENT Env 
