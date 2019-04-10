# RabbitMQ

[![Build Status](https://cloud.drone.io/api/badges/dockhippie/rabbitmq/status.svg)](https://cloud.drone.io/dockhippie/rabbitmq)
[![](https://images.microbadger.com/badges/image/webhippie/rabbitmq.svg)](https://microbadger.com/images/webhippie/rabbitmq "Get your own image badge on microbadger.com")

These are docker images for [RabbitMQ](https://www.rabbitmq.com/) running on an [Alpine Linux container](https://registry.hub.docker.com/u/webhippie/alpine/).


## Versions

* [latest](./latest) available as `webhippie/rabbitmq:latest`


## Volumes

* /var/lib/rabbitmq


## Ports

* 5671
* 5672
* 15671
* 15672
* 25672


## Available environment variables

```bash
ENV RABBITMQ_
```


## Inherited environment variables

* [webhippie/alpine](https://github.com/dockhippie/alpine#available-environment-variables)


## Contributing

Fork -> Patch -> Push -> Pull Request


## Authors

* [Thomas Boerger](https://github.com/tboerger)


## License

MIT


## Copyright

```
Copyright (c) 2019 Thomas Boerger <http://www.webhippie.de>
```
