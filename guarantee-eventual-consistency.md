# ADR-001: Use of Eventual Consistency

## Status

Accepted

## Date

YYYY-MM-dd

## Context

Our system is a distributed system that requires high availability. We have decided to use eventual consistency to ensure that data is replicated across multiple nodes in the system.

## Decision

We have decided to use eventual consistency because it allows us to achieve high availability while allowing for inconsistencies between nodes. This is important for our system because we need to ensure that the system remains available even if some nodes fail.

## Consequences

The use of eventual consistency may result in inconsistencies between nodes. However, we have decided that this is an acceptable tradeoff for achieving high availability.

## Alternatives

We considered using strong consistency to ensure that data is consistent across all nodes in the system. However, this would have required more resources and would have made it more difficult to achieve high availability.
