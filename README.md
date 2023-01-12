# CloudStudio

A demo of IRIS with CloudStudio (developed by Sean Connelly)

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
