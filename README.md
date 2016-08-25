# docker-gentoo-openldap
Dockerized net-nds/openldap

Basic usage:

```
$ docker run --rm -it -v /mnt/docker/ldap-server/etc/openldap:/etc/openldap -v /mnt/docker/ldap-server/data:/var/lib/openldap-data yakaes/docker-gentoo-nsd
```

