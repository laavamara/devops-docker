FROM ubuntu:16.04
RUN apt-get update && apt-get install -y curl git
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs
RUN git clone https://github.com/docker-hy/backend-example-docker
WORKDIR /backend-example-docker
EXPOSE 8000
ENV FRONT_URL=http://localhost:5000
RUN npm install
CMD ["npm", "start"]


