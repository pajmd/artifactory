# artifactory
cheatsheet
To upload
curl -u<USERNAME>:<PASSWORD> -T <PATH_TO_FILE> "http://localhost:8081/artifactory/generic-local/<TARGET_FILE_PATH>"
To download  
curl -u<USERNAME>:<PASSWORD> -O "http://localhost:8081/artifactory/generic-local/<TARGET_FILE_PATH>"
  
