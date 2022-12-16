# Complete_CI_CD_Project_03

I create an automated Docker CI pipeline that fetches java code from a repo on GitHub into Jenkins, builds and performs unit test using Maven, performs code analysis for bugs and code smells using SonarQube Scanner and builds the artifact. A docker image of the the artifact is built and published to Amazon ECR (Could be replaced with Google Container Registry (GCR), Azure Registry Servers, DockerHub, etc.). Then, as a continuation of Complete_CI_CD_Project_02, I add an extra stage in the PAAC for the deployment of the dockerized web app on Amazon ECS.
