1.docker build -t myjenkins-blueocean:2.414.2 .

2.docker network create jenkins

3.(this code for windows)docker run --name jenkins-blueocean --restart=on-failure --detach `
3.2.(this code for linux /macOS)docker run --name jenkins-blueocean --restart=on-failure --detach \

4.docker exec jenkins-blueocean cat /var/jenkins_home/secrets/initialAdminPassword
