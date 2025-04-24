# jenkins

## Installing and creating New Job Item in Jenkins
![image](https://github.com/user-attachments/assets/c8add69a-769a-4e1e-a5af-bef3e4f31d72)

## Source Code Management 
This is the Part where we select the url for any version control to fetch the data from.
As I was using github , I selected Git and Input URL with the credentials for accessing the repository
![image](https://github.com/user-attachments/assets/c08ce77e-82a7-4b22-bf0b-468e05ef669d)

## Select the Branch for the repository
![image](https://github.com/user-attachments/assets/8d42f470-ed67-478e-8625-2cd61bef699a)

## Enabling Triggers and WebHooks
For catching immediate update whenerver changes are made in the repository.
![image](https://github.com/user-attachments/assets/a5a193be-6e97-466e-ac2e-5ff994e48e89)

## Setup Build Steps and Environment
As it was a java developement project based on maven , Installed MAVEN , setup path for the new environment variables
Explicitely mentioned BUILD Commands for a cleaner build into .war file (Web Application Archive File)
![image](https://github.com/user-attachments/assets/0c388377-d38c-4232-b4b0-3bfcc62c1514)

## Checking logs for Successfully built!
![image](https://github.com/user-attachments/assets/cefa8b2d-f7fd-4c68-bfc6-2470f92ccd56)

![Screenshot (136)](https://github.com/user-attachments/assets/21623d86-24ae-441d-bcf9-2beb88fc58d3)

## Setting up post build actions to copy build file to tomcat(local)
![image](https://github.com/user-attachments/assets/a7e80649-2b1e-422c-9838-fd7d640bd4e1)
