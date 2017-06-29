# kibana-docker

Dockerfiles for the [`jaysong/kibana`](https://hub.docker.com/r/jaysong/kibana/)
Docker Hub images.

## Feature:

- Built on top of [`docker.elastic.co/kibana/kibana:5.4.1`](https://github.com/elastic/kibana-docker/tree/5.4).
- Removed [X-Pack](https://www.elastic.co/guide/en/x-pack/5.4/index.html).

## How-To:

### Start Kibana with Docker Compose

**Assuming the Elasticsearch setup at
[`jiaxing/elasticsearch-docker`](https://github.com/jiaxing/elasticsearch-docker)**

- Change directory to `dev`.
- To start Kibana, `docker-compose up -d`.
- Check it out at `localhost:5601`.
- To stop Kibana, `docker-compose down -v`.

## Notes:
1. [Found orphan containers](https://github.com/docker/compose/issues/3573)
