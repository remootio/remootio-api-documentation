# remootio-api-documentation

## Introduction

This repository was created to store the Remootio Websocket API documentation.
As the Remootio gets software updates, some new features also induce changes in the API. 
This is why you can find multiple versions of the API documentation.

Our goal while building the new API versions: new versions of the API shall be a superset of the original API, so all programs written based on the older API specification shall continue to work with the newer version.

## API versions used by specific Remootio software

The table below shows which API version is used by which Remootio software versions.

| Remootio software version  | API version |
|---|---|
| v1.00 - v2.20  | [v1](websocket_api_v1_specification.md) |
| v2.21 -   | [v2](websocket_api_v2_specification.md) |

## Short description of API versions

### Websocket API v2

Added more information to SERVER_HELLO frame
Increased the amount of log events emitted by Remootio

[View Websocket API v2 documentation](websocket_api_v2_specification.md)

### Websocket API v1

This is the initial API version.

[View Websocket API v1 documentation](websocket_api_v1_specification.md)
