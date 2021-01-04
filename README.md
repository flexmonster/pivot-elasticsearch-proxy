# Connect to Elasticsearch via proxy with Flexmonster Pivot Table & Charts
[![Flexmonster Pivot Table & Charts](https://cdn.flexmonster.com/landing.png)](https://flexmonster.com)
Website: www.flexmonster.com

## Flexmonster Pivot Table & Charts

Flexmonster Pivot is a powerful JavaScript tool for interactive web reporting. It allows you to visualize and analyze data from JSON, CSV, SQL, NoSQL, Elasticsearch, and OLAP data sources quickly and conveniently. Flexmonster is designed to integrate seamlessly with any client-side framework and can be easily embedded into your application.

This repository holds the source code for a project demonstrating how to connect Flexmonster to Elasticsearch via proxy:

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Prerequisites

To run the project, you will need Node.js and npm. [Get it here](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) if it's not already installed on your machine.

## Installation

1. Download the `.zip` archive with the sample project or clone it from GitHub with the following command:

```bash
git clone https://github.com/flexmonster/pivot-elasticsearch-proxy
cd pivot-elasticsearch-proxy
```

2. Install the npm packages described in `package.json`:

```bash
npm install
```

3. Start the sample proxy server:

```bash
npm start
```

4. Once the proxy server is running, open [`client/index.html`](https://github.com/flexmonster/pivot-elasticsearch-proxy/blob/main/client/index.html) in your browser. Note that the proxy processes all Flexmonster requests.


## Usage
 
For details on further configuration and usage, refer to the [Connecting to Elasticsearch](https://www.flexmonster.com/doc/connecting-to-elasticsearch/) guide.
