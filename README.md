# Docker Dev Environment

This is a docker environment for development. 

It contains : 
- MYSQL 8 : Database
- Mailcatcher : Sending mails during development
- Gotenberg : a API driver PDF converter
- Meilisearch : A search engine
- Minio : Local s3 server

## How it works: 

The docker-compose file contains all the services.
Of course Docker needs to be installed on your computer 😀

To start:

```
make start
```

To Stop : 
```
make stop
```

To recreate containers : 
```
make recreate
```



