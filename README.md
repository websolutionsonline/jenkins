# jenkins
Simple docker setup for Jenkins.

# Setup
open up your favourite command shell e.g. bash and navigate to this directory e.g. "cd /c/projects/jenkins"

run the following command:

    docker-compose up -d

Your instance of jenkins should then be viewable at: localhost:8080

The jenkins administrator password will be listed in your command shell.

# Docker Volume

A docker volume called 'jenkins_data' will be created to persist data when stopping and starting the container.

# Troubleshooting

1. if you encounter a blank screen after logging in or setting up a user for the first time simply navigate to: http://localhost:8080/restart and click yes to restart jenkins. This will resolve the blank screen issue.

Enjoy!