# sonarqube-docker
sonarqube in docker, using postgresql for database

## Steps to run 
1. Clone this project
2. Go inside the project : `cd sonarqube-docker`
3. Run command : `docker-compose up`
4. Now browse [http://localhost:9000](http://localhost:9000), you will see SonarQube home page.

## Analyse maven project using sonar
1. Go to root directory of your maven project
2. Run command : `mvn sonar:sonar`
3. Now browse [http://localhost:9000](http://localhost:9000) and see your project code quality.
