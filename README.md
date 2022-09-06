# major_project

Steps to set up docker swarm network:

1. Set up 4VMs with the required fabric software . Refer link - https://kctheservant.medium.com/setup-a-hyperledger-fabric-host-and-create-a-machine-image-682859fd58ba (Hyperledger Fabric Version 1.4.1) to get the idea of the process. 


Steps for hyperledger explorer:

1. cd explorer
2. docker-compose -f docker-compose.yaml up -d
(Always check logs of docker container for errors)
Open at : 0.0.0.0:8080

