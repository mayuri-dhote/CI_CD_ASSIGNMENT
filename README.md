# CI_CD_ASSIGNMENT

Create a Jenkins pipeline to deploy application present at: https://github.com/knoldus/node-hello
Required command to run the application and the ports being used are present in the Github repository.
You are required to use Jenkins Freestyle project to set this pipeline.
Requirements:
Jenkins should be set up on a Cloud Virtual Machine and not from the local system
Any commits to the ‘main’ branch should trigger the job on Jenkins and start the build process
Use Poll SCM triggers
The first part of the Jenkins job should be creating the package
The second part of the Jenkins job will be to send the package to another VM and run it there
The validations can be performed by hitting endpoints: <VM_IP>:3000 or <VM_IP>:3001

