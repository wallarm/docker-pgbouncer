Pgbouncer
=========

Pgbouncer - PostgreSQL connection pooler.
The Image contain pgbouncer version 1.9.0

Usage:
======

Mount your configuration directory as a volume:

```bash
  $ docker run -v <pgbouncer_config_dir>:/etc/pgbouncer \
               -v <pgbouncer_userlist_dir>:/etc/userlist \
               wallarm/pgbouncer
```
