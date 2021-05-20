# Graphql Metrics 

You can easily query information from a graphql endpoint using a [graphql](https://graphql.org/) playground. For a more concise, easy to get started dashboard. You can scrape any subgraph and export the data to [prometheus](https://prometheus.io/), where you can visualize the data in [grafana](https://grafana.com/). 

## Getting Started 

1. Edit the `prometheus/prometheus.yml` file with your subgraph endpoint and query
2. `docker-compose up -d`
3. View prometheus at `localhost:9090/graph` and grafana at `localhost:3000` 

You can view working code at [Lucas-Kohorst/theta-vault-metrics](https://github.com/Lucas-Kohorst/theta-vault-metrics) based on [this](https://api.thegraph.com/subgraphs/name/kenchangh/ribbon-finance/graphql) subgraph.