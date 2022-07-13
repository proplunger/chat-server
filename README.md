# Gise Video Chat Server 

[![Author](https://img.shields.io/badge/Author-vgiselbrecht-brightgreen.svg)](https://github.com/vgiselbrecht)
[![GitHub license](https://img.shields.io/github/license/vgiselbrecht/chat-server)](https://github.com/vgiselbrecht/chat-server/blob/master/LICENSE)
[![Sponsor](https://img.shields.io/badge/Sponsor-GitHub-ff69b4.svg)](https://github.com/sponsors/vgiselbrecht/)
![GitHub package.json version](https://img.shields.io/github/package-json/v/vgiselbrecht/chat-server)

node.js based server for [Gise Video Chat](https://github.com/vgiselbrecht/gise-video-chat/)

## Installing

```
git clone https://github.com/vgiselbrecht/chat-server.git chat-server
cd chat-server
npm install
```

## Configuration

The Chat Server can be configured with node.js environment variables (process.env).

* `CORS_ORIGIN` CORS origin URL to protect other URLs: default *
* `PORT` Port for the web-socket: default 8080

## Running

```
npm start
```

## Sponsoring

You can sponsor me through [GitHub Sponsoring](https://github.com/sponsors/vgiselbrecht/).

As a recognition, i would be happy to receive a star.

Suggestions and pull requests for extensions are always welcome.

## License

[Apache License 2.0](LICENSE)
