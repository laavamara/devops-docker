
`$ git clone https://github.com/docker-hy/spring-example-project`
`$ mv Dockerfile spring-example-project`
`$ cd spring-example-project`
`$ sudo docker build -t spring .`
`$ sudo docker run -d -p 8080:8080 spring`

Head to http://localhost:8080 to see that it's working
