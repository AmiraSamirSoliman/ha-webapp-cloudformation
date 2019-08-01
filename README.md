# Deploy a High-Availability Web Application using CloudFormation

Infrastructure as code that automates the process of creating a secured environment and deploying an application (packaged and uploaded into AWS S3 Storage) into a dockerized Apache Web Server. The script contains all the configurations needed for a repeatable process so that the infrastructure can be re-created and discarded at will multiple times.

### High-Level Specifications

`1.`  Four application servers: 2vCPUs, 4GB RAM, 10GB disk space.

`2.`  Linux Operating System using the Ubuntu machine image distribution.

`3.`  Servers are load-balanced with auto-scaling feature across two availability zones within a single region.

`4.`  Entry-point to the application is HTTP port 80.

`5.`  Bastion host to allow SSH to remote instances running within private subnets for debugging and troubleshooting production technical issues.


### Detailed Infrastructure Architecture






### Execution Requirements

`1.`  AWS account

`2.`  AWS CLI 

`3.`  Key-Pair
