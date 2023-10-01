# bitcoin_tracker_pipeline
👋 Hi there! I'm a data engineer working on a project that involves building a data pipeline to extract data from various sources, transform it, and load it into a data warehouse.
=======
# Bitcoin Monitor

This is an ETL pipeline to pull bitcoin exchange data from [CoinCap API](https://docs.coincap.io/) and load it into our data warehouse.

## Architecture

![Arch](assets/images/bc_arch.png)

We use python to pull, transform and load data. Our warehouse is postgres. We also spin up a Metabase instance for our presentation layer.

All of the components are running as docker containers.
