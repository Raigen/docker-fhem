# fhem house automation Docker Image for Raspberry Pi

### Usage

- **Pull** the respective **docker image** `$ docker pull raigen/rpi-fhem`
- Roll the container:
```
docker run -d -p 8083:8083 --name fhem raigen/rpi-fhem
```
- Finally configure your fhem instance via the web interface at **http://192.168.PI.PI:8083**.


I added a `docker-compose.yml` to the Github repository for launching the container.

### License

The MIT License (MIT), see [LICENSE](LICENSE) file.
