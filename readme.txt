docker image build -t homework .
docker container run -d --name web -p 8080:80 homework
