# jenkins-project

Step 1: docker-compose build  -> builds docker image (centos build server)

Step 2: docker-compose up -d  -> brings up the 2 containers (jenkins server and centos7 build server)

Step 3: configure jenkins server from the browser

  a. Install ssh plugin
  
  b. Add centos7 remote_user credentials.
  
  c. Add jenkins node (centos7 build server details)
  
  d. Create a jenkins pipeline job with SCM. 
