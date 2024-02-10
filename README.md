# Mifos X Platform Release 23.12 on Docker Compose

This setup is not for production environments!

This has been tested on Linux Ubuntu 22.04 LTS. Make sure you have Docker and Docker Compose plugin installed

For using MariaDB:

```console
cd mariadb
docker compose pull && docker compose down && docker compose up -d && docker compose logs -d
```


For using Postgresql;

```console
cd postgresql
docker compose pull && docker compose down && docker compose up -d && docker compose logs -d
```

After the services are up and running, it could take some minutes to start for the first time, open a Web Browser and go to


https://localhost


Use the default credentials for login:

User: mifos
Password: password