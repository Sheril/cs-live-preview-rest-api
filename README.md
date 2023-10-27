# Live Preview using REST API

[Live Preview](https://www.youtube.com/watch?v=SDZ8tR01yXw) allows content managers to preview the content changes in real-time before publishing or saving.

This code primarily focuses on how to setup Live Preview using REST API.

## Code Setup

- Add the Stack details in the constants.

## Prerequisites

1. Install [`http-server`](https://www.npmjs.com/package/http-server) as the Live Preview only runs on a secure server.
```bash
`npm install --global http-server`
```
2. Generate SSL certificate using the following command:
```bash
  openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
```
3. Run the following command to start the server:
```bash
http-server -S -C cert.pem
```
