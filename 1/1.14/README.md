`git clone https://github.com/docker-hy/rails-example-project`
`mv Dockerfile /rails-example-project`
`cd rails-example-project`
`sudo docker build -t ruby .`
`sudo docker run -d -p 3000:3000 ruby`
Head to http://localhost:3000 to see it work
