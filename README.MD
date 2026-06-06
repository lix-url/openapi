# Lix.li OpenAPI Specification

Official OpenAPI 3.1 specification for the Lix.li API.

![OpenAPI](https://img.shields.io/badge/OpenAPI-3.1-green)
![License](https://img.shields.io/badge/license-MIT-blue)

## Base URL

https://lix.li/api/1.0

## Authentication

```http
X-Api-Key: lix_live_xxx
```

## Available Resources

- Profile
- Links
- Groups

## Generate SDKs

Examples:

```bash
openapi-generator-cli generate \
  -i openapi.yaml \
  -g php \
  -o php-sdk
```

```bash
openapi-generator-cli generate \
  -i openapi.yaml \
  -g typescript-fetch \
  -o js-sdk
```
