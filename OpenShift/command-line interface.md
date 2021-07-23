## CLI commands
* to find the cli commands or the syntax to use ``` oc help ```  
* to view the Documentation ``` oc explain ``` 
*  to view the correct syntax and other options use ``` oc <command> --help ``` eg. ``` oc create --help ```
*  ``` oc new-project <project_name> --description="<description>" --display-name="<display_name>" ```
*  ``` oc project``` Lists all the Projects and the * signifies the current selected project 
*  ``` oc project <project_name>``` change to the given project
*  ``` oc new-app <git-repo>``` create a new project from git
*   ``` oc get pods``` check finished building
* ``` oc get all``` List all the resources within the projects
* ``` oc delete project <project_name>``` delete
* ### Import Export Resources
* Export resource to a yaml file ``` oc get -o yaml <resource> > <resource>.yaml``` 
* Create resource from a yaml file ``` oc create -f <resource>.yaml``` 
* Replace a resource ``` oc replace -f <file_name>```
* ``` oc get secrets```
* ``` oc extract secret <secret_name> --to=<directory_to_save>```






