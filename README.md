# Connect Flexmonster Pivot Table & Charts to Elasticsearch via a proxy server
[![Flexmonster Pivot Table & Charts](https://cdn.flexmonster.com/landing.png)](https://flexmonster.com)
Website: [www.flexmonster.com](https://www.flexmonster.com)

## Flexmonster Pivot Table & Charts

Flexmonster Pivot is a powerful JavaScript tool for interactive web reporting. It allows you to visualize and analyze data from JSON, CSV, SQL, NoSQL, Elasticsearch, and OLAP data sources quickly and conveniently. Flexmonster is designed to integrate seamlessly with any client-side framework and can be easily embedded into your application.

This repository contains a sample project demonstrating how to connect Flexmonster to Elasticsearch via a proxy server.

Table of contents:

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Related Flexmonster docs](#related-flexmonster-docs)

## Prerequisites

- [Node.js](https://nodejs.org/en/)

## Installation

1. Download a `.zip` archive with the sample project or clone it from GitHub with the following commands:

```bash
git clone https://github.com/flexmonster/pivot-elasticsearch-proxy
cd pivot-elasticsearch-proxy
```

2. Install the npm dependencies described in `package.json`:

```bash
npm install
```

3. Start the sample proxy server:

```bash
npm start
```

4. Once the proxy server is running, open [client/index.html](https://github.com/flexmonster/pivot-elasticsearch-proxy/blob/main/client/index.html) in your browser. Notice that the proxy server processes all Flexmonster requests.


## Related Flexmonster docs
 
- [Connecting to Elasticsearch](https://www.flexmonster.com/doc/connecting-to-elasticsearch/) — refer to this guide for details on Flexmonster configuration and usage.
