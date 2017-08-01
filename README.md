# MariaDB

[**Package DB** (owner)](https://admin.fedoraproject.org/pkgdb/package/modules/mariadb/) |
[**F26 modulemd** (source)](http://pkgs.fedoraproject.org/cgit/modules/mariadb.git/tree/mariadb.yaml?h=f26) |
[**PDC** (result)](https://pdc.fedoraproject.org/rest_api/v1/unreleasedvariants/?active=True&variant_name=mariadb)

MariaDB is a community developed branch of MySQL. MariaDB is a multi-user, multi-threaded SQL database server. It is a client/server implementation consisting of a server daemon (mysqld) and many different client programs and libraries. The base package contains the standard MariaDB/MySQL client programs and generic MySQL files.

## Current state

| State | Description |
|-------|-------------|
| ✓ YES | **Build passes** in the infra (all build deps are ok) |
| ✓ YES | **Installs** on the Base Runtime (all runtime deps are ok) |
| ✗ NO  | **No bootstrap** - uses only proper modules |
| ✓ YES | General **tests are in dist-git** |
| ✓ YES | General **tests pass** |
| ✗ NO  | Meets the **Fedora Module Packaging Guidelines** |

### Notes

See [**README**](https://github.com/container-images/mariadb) on github for more details. 

See [**hub.docker**](https://hub.docker.com/r/modularitycontainers/mariadb/) for Dockerimage. 
