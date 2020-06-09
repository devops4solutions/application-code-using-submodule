# Description
This is application repository which will store all the app code and use other repository as submodule for build and deployment

# How to 

  ## Add "submodule-config-repo" as submodule
   We are using "." before the folder name so that it is not visible by default
   ```
        git submodule add https://github.com/devops4solutions/submodule-config-repo.git .configs     
   ```
   After this command,make sure that all changes are in your repo and then push the changes. After you do the git push you should the .configs folder in this repository
   
# Use

 - You can copy all the config files directly at the root of the project using this command
       ```
       cp -rf .configs/* .
       ```



# Further reading
 
 - https://devops4solutions.com/application-code-and-deployment-code-in-different-repository-using-gitlabci-for-kubernetes-deployment/
 
