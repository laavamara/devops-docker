`git clone https://github.com/docker-hy/spring-example-project`
`mv Dockerfile spring-example-project`
`cd spring-example-project`
`sudo docker build -t spring .`
`sudo docker run -d -p 8080:8080 spring`
