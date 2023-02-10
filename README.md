Deploy to Elastic Beanstalk Project (With AWS , GitHub , Jenkins)

GitHub -> Jenkins -> Build/Compile -> Deploy -> AWS Elastic Beanstalk

1. Open AWS Elastic Beanstalk (High Availability)(Create Environments)
2. Create user in AWS With Access keys 
3. Create a new repository in Github ( Repository name : Deploy_to_Elastic_Beanstalk)
4. Create jenkins (name pipline: Deploy to Elastic Beanstalk Project (With AWS , GitHub , Jenkins) ( add plug : aws elastic beanstalk deployment)
in jenkins Add Credentials from aws user to connect 
ID_Credentials name : jenkins_for_elastic_beanstalk
5. Add webhook in Github for connect with jenkins
6. Add name  Application and Environment from AWS to Jenkins
7. when i upload file to github. its aotumatic go to jenkins and to Elastic Beanstalk
8. connect (Elastic Beanstalk)url to my domain (rout53)
Application name: Jenkins_app_2023
