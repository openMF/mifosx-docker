# Kubernetes manifests for use by mifos-gazelle 
The kubernetes manifests in this directory have been created using the "kompose" utility and initially used the mifosx-docker/mariadb/docker-compose.yml as src.   

# use / testing 
- see the mifos-gazelle readme for full instructions on deployment and testing 

## Notes
- These yaml files are intended to be maintained as part of the mifos-gazelle deployment tools 
- As mifos-gazelle is intended to reduce the resources needed to run MifosX, PHEE and (mojaloop) VNext the generated yamls for deploying MariaDB have been removed from this directory and are not maintained because mifos-gazelle uses combined and shared infrastructure services including the mysql database.
- ingress.yaml's have been added, and currently assume nginx ingress and ingressClassName