Run these commands with provided Dockerfile in your folder
`sudo docker build -t backend .`
`touch logs.txt`
`sudo docker run -it -p 8000:8000 -v $(pwd)/logs.txt:/backend-example-docker/logs.txt backend`
And head to http://localhost:8000. This will output logs.txt from app to your local working folder logs.txt file 
