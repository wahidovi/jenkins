# jenkins

This project is to demonstrate github docker and Jenkins pipeline

So when I push any change to my github repository it triggers Jenkins via webhooks 
and jenkins starts pulling the code with docker file in one EC2 instance. 
Then when that job is done it triggers another job which is to trigger 
another EC2 instance that runs a shell script to run the Docker container. 

