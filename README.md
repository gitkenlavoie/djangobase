# Django Base
This is an Alpine Linux file that can be utilized for Django builds.  

The demosite directory can be edited before build. The directory name will need to be changed before build, as this adds all of the Django settings into the Django environment. You will need to change the github location used with SVN

When you're ready to run: 

docker run -p 8000:8000 -it --rm <container name> 
  
As a reminder - /bin/ash for alpine linux cli. Bash is also installed with this base

