cd wordpress-docker
# Build and start installation
docker-compose up -d --build
```

Web site  <http://localhost/wordpress>  
database  phpMyAdmin <http://localhost:8080>

identification for wordpress website admin:

  - `Username: Dridi_Omar_Cv` and
  - `Password: kpqdwvtwNyk^3pv%MV` 

Default identification for the phpMyAdmin interface:

  - `Username: root` and
  - `Password: `

**Useful set of commands to know**:

``` bash
# Stop and remove containers
docker-compose down
# Build, and start the wordpress website
docker-compose up -d --build
# Reset everything
docker-compose down
rm -rf certs/* certs-data/* logs/nginx/* mysql/* wordpress/*
```

