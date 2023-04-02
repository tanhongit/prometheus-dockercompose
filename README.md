:whale Docker configuration for an instance of Prometheus using docker-compose.

# What is Prometheus?

Prometheus is a free software application used for event monitoring and alerting. It records metrics in a time series database built using an HTTP pull model, with flexible queries and real-time alerting.

This repository contains a docker-compose file to run Prometheus.

# Usage

Edit .env file and set the following variables:

```bash
APP_NAME=prometheus
APP_PORT=9095
```

To run Prometheus, execute the following command:

```bash
docker-compose up -d
```

# Configuration

The configuration file is located in the `prometheus` directory. The configuration file is named `prometheus.yml`.

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

[1]: https://prometheus.io/