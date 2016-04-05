# wildfly10-mariadb
Docker image with Wildfly 10 and MariaDB

Based on [jboss/wildfly:10.0.0.Final](https://hub.docker.com/r/jboss/wildfly/) and [million12/mariadb](https://hub.docker.com/r/million12/mariadb/)

- Starts a MariaDB database and creates a root user: `admin/admin`
- Starts Wildfly 10 and adds an admin user for the management console: `admin/Admin#007`
- Configures Wildfly to use MariaDB