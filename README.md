<p align="center">
  <img  src="https://raw.githubusercontent.com/rafaeldias97/api-netcore-v3/master/docs/netcore.png">
</p>

# API Modelo DDD

A Basic Example API DotNet Core 3.0, using DDD(Domain Driven Design), EntityFramework Core, Swagger, AutoMapper, IoC, Migration and JWT

## Environment
 Before everything, it must be installed and configured [Visual Studio 2019](https://visualstudio.microsoft.com/pt-br/vs/?rr=https%3A%2F%2Fwww.google.com%2F), [SDK 3.0](https://dotnet.microsoft.com/download/dotnet-core/3.0) and [Docker](https://docs.docker.com/docker-for-windows/install/)

## Running and Migration
To run Database you need to start Docker, and go to project root path and run the command:

> docker-compose up

* #### Execute Migration
To run Migration open project in Visual Studio 2019 > Package Manager Console > Select "APIModeloDDD.Infra.Data" and execute

> Add-Migration Migation_Name
> Update-Database

After all the project must be executed on Visual Studio 2019

## JWT Config
To configure JWT (Json Web Token), to must be replaced the object JWT in APIModeloDDD.Presentation > appsettings.json

![](https://raw.githubusercontent.com/rafaeldias97/api-netcore-v3/master/docs/appsettingsjwt.PNG)

## Swagger Interface
Swagger document all endpoints of the WEBAPI

![](https://raw.githubusercontent.com/rafaeldias97/api-netcore-v3/master/docs/Swagger.PNG)