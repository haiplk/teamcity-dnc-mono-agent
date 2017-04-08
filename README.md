## TeamCity Dotnet Core & Mono Agent Image Dockerfile

This project contains the Dockerfile and all necessary scripts to build the Docker image and run a TeamCity Build Agent that can support Microsoft Dotnet Core and Mono builds inside the container.

The Dockerfile currently installs Dotnet Core version 1.0.1, which as of creation is the current version of Dotnet Core, and Mono 4.8, which as of creation is the current version of Mono.

You can pull the ready-to-use image from the Docker Hub repository
                                     
`docker pull github.com/richardprice/teamcity-dnc-mono-agent`

This is based on the TeamCity standard agent, viewable here:

`https://github.com/JetBrains/teamcity-docker-agent`