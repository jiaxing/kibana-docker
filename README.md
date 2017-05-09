# kibana-docker

Dockerfiles for the [`jaysong/kibana`](https://hub.docker.com/r/jaysong/kibana/)
Docker Hub images.

## Feature:

- Built on top of [`docker.elastic.co/kibana/kibana:5.4.0`](https://github.com/elastic/kibana-docker/tree/5.4).
- Removed [X-Pack](https://www.elastic.co/guide/en/x-pack/5.4/index.html).

## How-To:

### Start a service with Docker Compose

Change directory to `dev`.

- To start service, `docker-compose up -d`
- To stop the service, `docker-compose down`
- To destroy service and data, `docker-compose down -v`
