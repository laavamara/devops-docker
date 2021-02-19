Edit: Actually realized I deleted Dockerfile so I'll skip this assignment

`$ git clone https://github.com/docker-hy/spring-example-project`
Run these in folder with Dockerfile
`$ sudo docker build -t spring .`
`$ sudo docker run -d -p 8080:8080 spring`

Head to http://localhost:8080 to see that it's working
