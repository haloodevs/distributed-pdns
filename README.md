# PowerDNS with MariaDB backend Production-ready on Kubernetes cluster

<p align="center"><img src="images/powerdns.jpg"/></p>

The ultimate goal of this repository: A distributed PowerDNS with MariaDB-Galera cluster backend

## Requirements
 . A reliable Kubernetes cluster

 . Basic knowledge of Kubernetes kinds and deployments

 . Familiar with MariaDB database configuration

 . Familiar with DNS services and how it works

## Development Steps

### Single Deployment on K8s
1. Write manifest to deploy MariaDB on Kubernetes cluster
2. Basic Configuration of MariaDB deployment, by setting MariaDB-configmap
3. Write manifest to deploy PowerDNS on Kubernetes and connect to MariaDB-service
4. Write manifest to deploy PowerDNS-Webadmin panel on Kubernetes cluster

### Future Development (Distributed and Production-ready DNS Service)

1. Change MariaDB deployment with replica 1 to Mariadb multi-primary and Statefulset with replica 3
2. Change PowerDNS deployment with replica 1 to Distributed PDNS with replica 3
3. Change Webadmin single deployment to Distributed and reliable service 


## Contribute 

Dear Developers and Contributors,

You can contribute to this repo by doing future development tasks. We'll create issues for future project developments. 

