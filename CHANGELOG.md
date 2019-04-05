# Radiks-Server Changelog

## 0.1.10 - April 1, 2019

- Support for adding a `maxLimit` configuration to radiks, so that you can limit the maximum number of records that can be fetched from the API. Thanks to @pradel for [their contribution!](https://github.com/blockstack-radiks/radiks-server/pull/5)

## 0.1.9 - March 25, 2019

- Added support for deleting models

## 0.1.8 - March 1, 2019

- Fixes a bug where saving data wouldn't work in Firefox. This was due to Firefox not accepting a wildcard (`*`) for the `Access-Control-Allow-Headers` response header.
  - New allowed headers: `origin`, `content-type` 