![logo](https://raw.githubusercontent.com/jsontp/logo/master/logos/jsontp-social.jpg)
<h3 align="center">The newest web protocol, using JSON, the ubiquitous format. </h2>

## current version: [`1.0-rc2`](https://github.com/jsontp/paper/blob/main/paper.md)


`jsontp` is an protocol that uses `json` as its data interchange format over `tcp`

## the `jsontp` protocol
- there are two types of `jsontp` messages: **`request` and `response`**
- a `request` message is sent from client to server, and a `response` message is sent from server to client

it supports the HTTP methods:
- `GET`
- `POST`
- `PUT`
- `DELETE`
- `OPTIONS`

It also has support for `"expect": "100-continue"`, `set-cookies`, `lanugauge`, and `date`.
It ensures that the requests are always folowing the same format, making it easy to use in applications.
