# Cloud Studio

## Introduction

Welcome to an early Preview release of Cloud Studio, a code editor for M routines and globals in Iris. Documentation will follow an Alpha release.
The project is currently "work in progress" and is at the early stages of development and testing. Plan is for integration with other M implementations.  Open source and free to use and modify with no restriction. Author:  Sean Connelly 

[Video Demonstration](https://www.youtube.com/watch?v=Am6QAvrPPPg)

![Cloud Studio Demonstration](./npc/Screeshot.jpg)


## Gitpod
 [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/RamSailopal/Intersystems-CloudStudio)  
 
then navigate to:

https://52773-<gitpod server address\>/cloudstudio/CloudStudio.Index.cls  
where  
\<gitpod server address\> = ramsailopal-intersystem-xxxxxxxxxxx.ws-us81.gitpod.io  

Change the password on request from:  
Username: **_SYSTEM**  
Password: **SYS**  

# Local

     docker run --name my-iris -p 52773:52773 -d ramb0/cloudstudio --check-caps false
then navigate to:  
http://localhost:52773/cloudstudio/CloudStudio.Index.cls

Change the password on request from:  
Username: **_SYSTEM**  
Password: **SYS**  

# References  
https://github.com/SeanConnelly/CloudStudio  
https://hub.docker.com/r/ramb0/cloudstudio
