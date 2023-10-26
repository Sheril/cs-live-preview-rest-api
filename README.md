# Live Preview using REST API

Live Preview allows content managers to preview the content changes in real-time before publishing or saving. This is an example for how to use Live Preview using Contentstack Delivery API.

## Setup

- Add the environment variables.

## Prerequisites

1. [Install `http-server`](https://www.npmjs.com/package/http-server) `npm install --global http-server`
2. Generate SSL certificate using the following command:
```bash
  openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
```
3. Run the following command to start the server:
```bash
http-server -S -C cert.pem
```
