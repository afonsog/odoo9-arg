# odoo9-arg

Docker image of odoo Argentina.
It contains all the necessary dependencies to support the installation of the modules that the application contains.

## Docker-compose

Create the volumes used by the application:

```bash
docker volume create --name=odoo_data
docker volume create --name=database_data
```

Start the application:
```bash
docker-compose up -d
```

In the browser, enter the application via http://localhost:8069
