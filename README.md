# docker-squid

Squid is a caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages. Squid has extensive access controls and makes a great server accelerator. It runs on most available operating systems, including Windows and is licensed under the GNU GPL. (http://www.squid-cache.org/)

## Build

```bash
docker build -t docker-squid github.com/engelhardtm/squid
```

## Quickstart

```bash
docker run -d -p 3128:3128 engelhardtm/squid
```
