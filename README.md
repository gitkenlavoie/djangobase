# Django Base
This is an Alpine Linux file that can be utilized for Django builds.  

The demosite directory can be edited before build. The directory name will need to be changed before build, as this injects all of the Django settings into the Django environment. 

When you're ready to run: 

docker run -p 8000:8000 -it --rm <container> 
  
As a fyi - /bin/ash for alpine linux cli. Bash is installed with this 

