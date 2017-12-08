# ng-2-docker-nginx

Running Angular applications inside a Docker container

#### Start
- Make sure you have NPM installed on your system.
- Install AngularCLI by running npm install -g @angular/cli.
#### Building a image

		 docker build -t ng-2-docker/client .
#### Running a docker-compose 

 		docker-compose up -d --build --remove-orphans

 got to: http://localhost (nginx)