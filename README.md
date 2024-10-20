# pretix-docker_compose

Than run the docker-compose file and create a new cronjob to run the internal pretix jobs.

```
15,45 * * * * /usr/bin/docker exec pretix_app pretix cron
```

## Default credentials

- User: admin@localhost
- Password: admin

Change this settings!
