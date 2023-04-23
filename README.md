# python-web-pyramid-api-cockroachdb-single-node-without-ssl-simple

## Description
Simple web app that serves an api
for a pyramid project.

Uses sqlalchemy query a table `dog`.

Remotely tested with *testify*.

## Tech stack
- python
  - pyramid
  - sqlalchemy
  - testify
  - requests
- cockroachdb

## Docker stack
- python:latest
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- Endpoints
    - [Html](http://localhost)
    - [Api](http://localhost/dog)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Pyramid setup](https://docs.pylonsproject.org/projects/pyramid/en/latest/index.html)
- [Sqlalchemy setup](https://docs.pylonsproject.org/projects/pyramid-cookbook/en/latest/database/sqlalchemy.html)
- [Json setup](https://docs.pylonsproject.org/projects/pyramid/en/latest/narr/renderers.html)
