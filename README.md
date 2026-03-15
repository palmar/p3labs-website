# P3 Labs Website

Public website for P3 Labs at [p3labs.palmar.is](https://p3labs.palmar.is).

## What is this?

A static website — plain HTML and CSS. No build step, no dependencies, no framework.

## Deploy

Serve the root directory with any static file server (Caddy, nginx, etc).

Example Caddy config:
```
p3labs.palmar.is {
    root * /var/www/p3labs
    file_server
}
```

## License

MIT
