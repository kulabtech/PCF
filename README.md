CICD Using Jenkins Pipeline and Pivotal Web Services / Pivotal Cloud Foundry
- `Jenkinsfile` controls the Jenkins Pipeline. More stages can be added into this file
- `/hello` REST endpoint returns a message
- Command to deploy into PCF/PWS
# testing cic/cd file from CF plugin
    
        cf login -a https://api.run.pivotal.io -u <user_name> -p <password>
        cf target -o testing -s allstatepoc
        cf push -f <path_to_manifest_yml>
        
        
        
