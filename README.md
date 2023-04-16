## This example shows how to build a simple LDAP server embedded into a Spring Boot application

Once started, server will be available on port 8389

Credentials that can be used to log in:
```yaml
base-dn: dc=testad,dc=local
credential:
  username: uid=admin
  password: secret
```

### Useful links
* [LDAP Wiki](https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol)
* [LDIF Filter Examples](https://confluence.atlassian.com/kb/how-to-write-ldap-search-filters-792496933.html)
* [Spring LDAP Authentication](https://docs.spring.io/spring-security/site/docs/4.2.x/reference/html/ldap.html)
* [Authenticating a User with LDAP (guide)](https://spring.io/guides/gs/authenticating-ldap/)

