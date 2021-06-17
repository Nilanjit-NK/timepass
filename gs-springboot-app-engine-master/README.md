# Spring Boot Application Google App Engine Standard with Java 11
Developed Spring Boot Application integrated with PostgreSQL to that be deployed to Google App Engine Standard
                          
     $ mvn clean package
     $ mvn spring-boot:run 
     
Open localhost:8080/

## Deploying to Google Cloud
```bash
   $ gcloud app deploy
```

To view your app, use command:
```
  $ gcloud app browse
```
Or navigate to `https://<your-project-id>.appspot.com`.
