# monitor-swagger-stats-with-grafana

<p align="center">
<img src="https://github.com/slanatech/swagger-stats/blob/master/screenshots/logo.png?raw=true" alt="swagger-stats"/>
</p>

# swagger-stats | API Observability

#### [https://swaggerstats.io](https://swaggerstats.io) | [Guide](https://swaggerstats.io/guide/)

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/slanatech/swagger-stats/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/slanatech/swagger-stats/tree/master)
[![Coverage Status](https://coveralls.io/repos/github/slanatech/swagger-stats/badge.svg?branch=master&dummy)](https://coveralls.io/github/slanatech/swagger-stats?branch=master&dummy)
[![npm version](https://badge.fury.io/js/swagger-stats.svg)](https://badge.fury.io/js/swagger-stats)
[![npm downloads](https://img.shields.io/npm/dm/swagger-stats.svg)](https://img.shields.io/npm/dm/swagger-stats)
[![Gitter](https://badges.gitter.im/swagger-stats/community.svg)](https://gitter.im/swagger-stats/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

#### Trace API calls and Monitor API performance, health and usage statistics in Node.js Microservices

### Express, Fastify, Koa, Hapi, Restify

**swagger-stats** traces REST API requests and responses in Node.js Microservices, and collects statistics per API Operation.
**swagger-stats** detects API operations based on express routes. You may also provide [Swagger (Open API) specification](https://swagger.io/specification/),
and swagger-stats will match API requests with API Operations defined in swagger specification.

#

![Grafana Logo (Light)](https://github.com/grafana/grafana/raw/main/docs/logo-horizontal.png#gh-light-mode-only)

The open-source platform for monitoring and observability

[![License](https://img.shields.io/github/license/grafana/grafana)](LICENSE)
[![Drone](https://drone.grafana.net/api/badges/grafana/grafana/status.svg)](https://drone.grafana.net/grafana/grafana)
[![Go Report Card](https://goreportcard.com/badge/github.com/grafana/grafana)](https://goreportcard.com/report/github.com/grafana/grafana)

Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored. Create, explore, and share dashboards with your team and foster a data-driven culture:

- **Visualizations:** Fast and flexible client side graphs with a multitude of options. Panel plugins offer many different ways to visualize metrics and logs.
- **Dynamic Dashboards:** Create dynamic & reusable dashboards with template variables that appear as dropdowns at the top of the dashboard.
- **Explore Metrics:** Explore your data through ad-hoc queries and dynamic drilldown. Split view and compare different time ranges, queries and data sources side by side.
- **Explore Logs:** Experience the magic of switching from metrics to logs with preserved label filters. Quickly search through all your logs or streaming them live.
- **Alerting:** Visually define alert rules for your most important metrics. Grafana will continuously evaluate and send notifications to systems like Slack, PagerDuty, VictorOps, OpsGenie.
- **Mixed Data Sources:** Mix different data sources in the same graph! You can specify a data source on a per-query basis. This works for even custom datasources.

## Description

This project uses Express and Swagger Stats to provide API monitoring and reporting.

## Installation

To install the dependencies, run the following command:

```bash
npm install
```

```bash
docker-compose up
```

## Running the app

```bash
$ npm run dev
```
