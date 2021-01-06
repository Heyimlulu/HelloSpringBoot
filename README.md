# HelloSpringBoot

My first springBoot Application

## Build

- Right click on project root directory
- Run As
  - Run Configurations
  
- Select Maven Build in the right menu
  - Base directory will be the project location
  - Goals
    - install
  - Profiles
    - pom.xml
- Click Run
  
<img height="500px" src="https://image.noelshack.com/fichiers/2021/01/3/1609923360-2021-01-06-09h49-35.png">

```
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  6.814 s
[INFO] Finished at: 2021-01-06T09:44:09+01:00
[INFO] ------------------------------------------------------------------------
```

## Running App

- Right click on project root directory
- Run As
  - Spring Boot App
- Now it should run if you go to **localhost:8888**

  ```
  2021-01-06 09:44:38.900  INFO 12680 --- [main] o.o.h.HelloSpringBootApplication : Started HelloSpringBootApplication in 3.71 seconds (JVM running for 4.574)
  ```
  
  <img height="200px" src="https://image.noelshack.com/fichiers/2021/01/3/1609923791-2020-12-09-16h06-25.png">
