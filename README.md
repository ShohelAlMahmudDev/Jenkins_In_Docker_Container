# Jenkins_In_Docker_Container

#Step 1: Install the Docker Desktop on your machine. for more details and instructions please go through the following link
https://docs.docker.com/desktop/

#Step 2: 
Run the below command to download and install jenkins image and run the container
docker run -p 8080:8080 -p 50000:50000 -d -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts
