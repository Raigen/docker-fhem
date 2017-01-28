# fhem house automation docker image

### Usage

- **Pull** the respective **docker image** `$ docker pull raigen/fhem`
- Roll the container:
```
docker run -d -p 8083:8083 --name fhem raigen/fhem
```
- Finally configure your fhem instance via the web interface at **http://192.168.xxx.xxx:8083**.


I added `docker-compose.yml` files to the Github repository for launching the container.

### License

The MIT License (MIT), see [LICENSE](LICENSE) file.
