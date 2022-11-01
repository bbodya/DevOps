Login(Authorization) <br />
docker login <br /><br />
  Create a container <br />
docker build -t bbodya/devops . <br /><br />
  Upload to Docker <br />
docker push bbodya/devops <br /><br />
  Run <br />
docker run -p 80:80 --name my-container --cpu-period=50000 --cpu-quota=25000 --memory=256m bbodya/devops
