# artifactory
## cheatsheet  

To start  
~/artifactory-oss-6.12.2/bin$ ./artifactory.sh   

URL  
http://localhost:8081/artifactory  

credentials  
admin/password

  
To upload  
curl -u<USERNAME>:<PASSWORD> -T <PATH_TO_FILE> "http://localhost:8081/artifactory/generic-local/<TARGET_FILE_PATH>"  
   
To download     
curl -u<USERNAME>:<PASSWORD> -O "http://localhost:8081/artifactory/generic-local/<TARGET_FILE_PATH>"
  
