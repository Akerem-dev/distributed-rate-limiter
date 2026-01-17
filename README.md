# Distributed Rate Limiter

A distributed rate limiting service backed by Redis. Supports multiple limiting algorithms and is designed to be measurable (latency/RPS) and testable.

## Goals
- Multiple algorithms: Fixed Window, Sliding Window, Token Bucket
- Atomic operations via Redis Lua scripts
- Metrics endpoint for observability
- Load testing with k6

## Planned Tech
- Java 17
- Spring Boot
- Redis
- k6
