Run backend in its own container
`sudo docker build -t back .`
`sudo docker run -d -p 8000:8000 back`
