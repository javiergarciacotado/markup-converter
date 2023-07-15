# ADR-002: Use of OpenAPI Documents as the source of truth for Operator Management REST API

## Status

Accepted

## Date

YYYY-MM-dd

## Context

Our system is a REST API that requires consistency across all endpoints. We have decided to use OpenAPI documents as the source of truth for our API.

## Decision

We have decided to use OpenAPI documents as the source of truth for our REST API because they provide a standardized way to describe our API. This allows us to ensure consistency across all endpoints and makes it easier to maintain our API over time.

## Consequences

The use of OpenAPI documents may require additional resources upfront to create and maintain. However, we have decided that this is an acceptable tradeoff for ensuring consistency across our REST API.

## Alternatives

We considered using other documentation formats such as Swagger or RAML. However, we decided that OpenAPI was the best choice because it is widely adopted and provides a standardized way to describe REST APIs.
